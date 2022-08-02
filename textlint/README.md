# Textlint による文章校正

[TRANSLATION-POLICY.md](https://github.com/InnerSourceCommons/japanese-contents/blob/main/TRANSLATION-POLICY.md) に示された翻訳のポリシーを実現するため、Textlint という文章校正ツールを用います。
文体と語彙を統一し、平易な文章を書くために役立ちます。

## 使用準備

[Node.js](https://nodejs.dev/) が必要です。各自の環境に合わせてご準備ください。

Textlint 本体と、校正対象ルールのパッケージをインストールします。
(必要なパッケージについては package.json で管理しています。)

```
$ cd (path to your clone of this repository)
# npm install
```

## 使用方法

コマンドラインで校正対象の文書ファイルを指定します。
以下は翻訳者がクローンした jp-contentes リポジトリにて、Getting Started with InnerSource の日本語版を校正する例です。

```
$ cd (path to your clone of this repository)
$ npm run lint Getting-Started-with-InnerSource/ja.md
```

`npm run lint` に続いて校正対象のファイルを指定してください。

`npm run lint "**/ja.md"`のように正規表現を用いてファイルを指定することも可能です。

npm script 内で設定ファイルとして`.textlintrc` というファイルを指定しています。
このファイルは校正内容を記すものです。

## 結果の例

Textlint を実行すると、校正提案箇所が行と文字数で示されます。
また、その箇所に何の校正内容が求められるかが示されます。
校正内容には severity (深刻度) があり、error が高く、warning が低いものとなっています。
そして、どのルールに基づいて校正が提唱されているかが示されます。

以下は、213行目の28文字目の文の長さが121文字であり、設定された最大値120文字を超えているという warning です。関連ルールは ja-technical-writing/sentence-length であることも示されています。

```
213:28   warning  Line 213 sentence length(121) exceeds the maximum sentence length of 120.
Over 1 characters  ja-technical-writing/sentence-length
```

以下は、40行目の51文字目に冗長な表現があるという error が示されています。

```
40:51   error    【dict5】 "リリースを行う"は冗長な表現です。"リリースする"など簡潔な表現にすると文章が明瞭になります。
解説: https://github.com/textlint-ja/textlint-rule-ja-no-redundant-expression#dict5                        ja-technical-writing/ja-no-redundant-expression
```

全ての校正提案箇所が示された最後に、その数がまとめられます。
以下は 30 件の error と 9件の warning がある例です。

```
✖ 39 problems (30 errors, 9 warnings)
✓ 16 fixable problems.
Try to run: $ textlint --fix [file]
```

また、この例にあるように、一部の校正提案箇所は `--fix` オプションによって修復することができます。
ただし、どのように修復されるかは校正対象ルールのパッケージによって定められているものであり、必ずしも望む通りに修復されるわけではないことに注意してください。
また、修復範囲はファイル全体です。複数人で編集しているファイルをこのオプションで修復すると、自分の担当外の箇所も修復されることに注意してください。

## 校正内容の設定方法

Textlint が提案する校正内容は .textlintrc という JSON 形式の設定ファイルによって定められます。
校正内容は rules と filters に分かれ、rules に守りたいルールを、filters にその例外を記します。多くは rules に書くことになるでしょう。

### 用語の統一

[prh(proofreading helper)](https://github.com/textlint-rule/textlint-rule-prh) という仕組みを用いて実現します。
用いたい用語と禁止したい用語を yaml ファイルに記し、そのファイルを .textlintrc に指定します。

### 文章の校正

文体の統一や、1文あたりの長さの限定といった文章の校正は、校正ルールをまとめたプリセットと、それに含まれるルールごとの設定を記述することで実現します。

本プロジェクトでは以下のプリセットを採用します。

* [textlint-rule-preset-ja-technical-writing](https://github.com/textlint-ja/textlint-rule-preset-ja-technical-writing)

.textlintrc では、プリセットに含まれる各ルールの有効/無効、逸脱と判定するしきい値の変更、error/warning の選択を記すことができます。

### 例外の指定

[allowlist](https://github.com/textlint/textlint-filter-rule-allowlist) という仕組みを用いて実現します。
