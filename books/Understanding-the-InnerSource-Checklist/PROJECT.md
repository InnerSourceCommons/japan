# Understanding the InnerSource Checklist 翻訳プロジェクト

このドキュメントは、[Understanding the InnerSource Checklist](https://innersourcecommons.org/learn/books/understanding-the-innersource-checklist/) を日本語に翻訳するプロジェクトについて記したものです。
以下の構成としています。

- 背景
	- なぜ翻訳するのか？
- 目標
	- 翻訳によって何を達成しようとしているのか？
- 方法
	- どうやるのか？
- 日程
	- いつやるのか？
- メンバー
	- 誰がやるのか？何の権限を持つか？

## 背景

[InnerSource Commons はいくつかの本を提供しています。](https://innersourcecommons.org/learn/books/)
これらのうち、InnerSource Patterns は[インナーソースパターン](https://patterns.innersourcecommons.org/v/ja/)として公開され、Getting Started with InnerSource も[翻訳が終わり](https://github.com/InnerSourceCommons/jp-contents/tree/main/books/Getting-Started-with-InnerSource)、インナーソース入門として公開される予定です(2022年10月3日現在)。

今後も、日本におけるインナーソースの理解と実践を育むべく、翻訳を続けていきます。
これらの次に翻訳する本としては、[Understanding the InnerSource Checklist (以下、本書)](https://innersourcecommons.org/learn/books/understanding-the-innersource-checklist/)が最適であると考えています。
本書もインナーソース入門と同じく入門的な内容ですが、インナーソースとは何か？何の価値があるのか？という疑問に答える内容になっていることが特徴です。
また、インナーソース入門が PayPal 社の事例に焦点を当てているのに対して、本書ではより一般的な方法を記しています。
ですから、本書はインナーソースを初めて学ぶ人々にとって重要な位置にいると考えています。

本書の分量は60ページであり、一般的な書籍に比べて少ない点も本書を選択した理由の一部です。
InnerSource Commons で日本人の参加が加速し始めた2022年7月以降、初めて翻訳された本が22ページのインナーソース入門でした。
インナーソース入門の翻訳では、インナーソースに初めて出会った方、翻訳に初めて挑戦する方が多く参加されました。
この経験は、InnerSource Commons における日本人の初期活動として記念すべき一歩と言ってもよいでしょう。
そして、本書の翻訳はそうしたコミュニティメンバーの成長のためにも適していると考えています。

最後の背景として、@yuhattor が本書の翻訳について O'Reilly Media 社との交渉を成功させ、同社から得られた翻訳承諾を示すメッセージを以下に記します。

```
O'Reilly Media, Inc. is pleased to grant you the non-exclusive rights to translate our title, Understanding the InnerSource Checklist, into the Japanese language, to be published online under a Creative Commons Attribution-NonCommercial-NoDerivatives (CC-BY-NC-ND) license, and provided you charge no fee for access to the translation.

Please make sure to include the following credit line on the webpage where the translation will be published: "Understanding the InnerSource Checklist, by Silona Bonewald. Copyright (C) 2017 O'Reilly Media.
Published by O'Reilly Media, Inc. Translated with permission"

When completed, we ask that you provide us a link to your posting for referencing in our permissions records.
You will need to cite at the beginning of the material as being a translation of the English edition and provide a link where the English version can be found on our platform:
https://learning.oreilly.com/library/view/understanding-the-innersource/9781491986899/copyright-page01.html

Additionally, you must create your own cover (if applicable) and it should not look similar to the English language cover.
Your cover should not display any O'Reilly branding or logos.
We reserve the right to modify or supplement there terms.
```

## 目標

本書の翻訳を通じて以下の目標を達成します。

- Understanding the InnerSource Checklist を日本語に翻訳して一般に無償で公開すること
	- 直接的であり第一の目標はこれです。
	- Gitbook または PDF として公式にリリースし、原稿も GitHub で公開することになるでしょう。
- 本プロジェクト参加者のインナーソースに対する理解が向上すること
	- インナーソース入門の翻訳参加者からは、翻訳を通じてインナーソースに対する理解が向上したという意見が寄せられました。(Issue #43)
	- 本書の翻訳でも同じく理解の向上を目指します。
- 新しいコントリビューターが増えること
	- 2022年7月以来、InnerSource Commons に参加し始めた日本人は増えています。何かしらのコントリビューションをしてみたいという潜在層がいることでしょう。
	- そうした方々に機会を提供し、新しいコントリビューターが増えることを目指します。
- 新しい日本語コンテンツのトラステッドコミッターが増えること
	- 本プロジェクト発足時点では、日本語コンテンツのトラステッドコミッターは2人です。
	- 本プロジェクトを通じて、日本語コンテンツの十分な作成能力を持ち、継続的にコントリビューションのできる人(つまりトラステッドコミッター)を1人以上増やすことを目標とします。
- 成果を国際コミュニティに伝えること
	- 本プロジェクトのほとんどは日本人に閉じた活動になる見込みです。ただ、InnerSource Commons は国際コミュニティであるため、成果を特定の言語圏のみで共有するのではなく、広く伝えることが求められるでしょう。

## 方法

目標を達成する方法を記します。

### チーム

このプロジェクトはチームで、すなわち同じ目標を共有する複数人で進めます。
チームメンバーは翻訳を担当する本書の構成要素を選び、分担します。

| 構成要素 | 量(pages) | 翻訳メンバー(GitHub / Slack name) |
|----|----|----|
| Forward | 1 | masskaneko / Mass Kaneko |
| 1. Why InnerSource | 6 | ystk / Yoshitake Kobayashi |
| 2. What InnerSource Is and Isn't | 6 |  |
| 3. The Most Important Role, and the First Step: Trusted Committer | 5 | yuhattor / Yuki Hattori |
| 4. Passive Documentation and the Need for Findability | 3 | bory-kb / Shoma Kubo |
| 5. Creating Good House Rules for Guests: Writing Contributing Agreements | 4 | mura-mi / Takuya Murakami |
| 6. Working Within the Enterprise: Understanding Planning | 6 | shrimp78 / Yoshiaki Kitamura |
| 7. From Internal Silos to Internal Transparency | 6 |  |
| 8. Looking Forward | 2 |  |
| 9. Appendix | 9 | hiromotai7 / HiroMotai |

チームメンバーの募集は InnerSource Commons の Slack チャンネル `#jp-general, #jp-contents` で行います。
これにより、新しいコントリビューター、継続的なコントリビューターが増えることを期待します。

リーダーは @masskaneko が務めます。

Appendix については [InnerSource Commons によるものではない日本語訳](https://elinux.org/images/3/3d/Checklist.ja-9f733d2f6e9b.pdf) が存在します。
ただ、我々 InnerSource Commons がこれを転用できる権利を得られるか定かではありません。
また、本プロジェクトがより良い訳を考える機会であると捉え、新たに訳すことにします。

### 訳文の作成

[本プロジェクトのフォルダ](books/Understanding-the-InnerSource-Checklist/)では、本書の構成要素ごとに Markdown ファイルを設けています。
これらの Markdown ファイルを原稿とし、訳文を作成していきます。

まず、担当する構成要素のファイルと同じ名前のブランチを作成し、そのブランチ上で対応する構成要素の編集をします。
例えば、1章を担当するメンバーは、`1-why-innersource` というブランチで `1-why-innersource.md` を編集します。
それ以外の構成要素を編集しないでください。

本書構成要素の Markdown ファイルには原文をコメントアウトして載せています。
原文を見ながら訳文を作成するのに役立つでしょう。

本プロジェクトでは、[本リポジトリ共通の翻訳ポリシー](../../TRANSLATION-POLICY.md)に従います。一読ください。

最初から DeepL や Google Translator といった機械翻訳を用い、その結果をもとに訳文を作成する方法はお止めください。
これらのツールでは概ね自然に感じられる訳文が得られますが、そうでないこともあります。
自然に感じられる訳文であっても、意味が誤っていることもあります。
特に本書のような専門書では顕著です。
訳者も、原文を理解する機会と訳文の構造を考える機会を失います。

### レビュー

[翻訳ポリシー](../../TRANSLATION-POLICY.md) にあるレビューポリシーに沿い、Pull Request を用いたレビューをします。
ある章の担当者は、その次の章のレビュアーを担います。
こう割り振ることで、自身の書いた内容が次の章に文脈上つながるかを判断しやすくなることが狙いです。

他の共訳者も任意のレビューに自由に参加できます。
自身の担当する章と関係のありそうな章のレビューに参加するのがよいでしょう。

### 監訳

翻訳する人数が増えるほど、用語や質の整合性をとる必要が出てきます。
これを監訳と呼び、本プロジェクトでは @masskaneko が監訳者を担います。
監訳者は、共訳者同士のレビューに参加することがあります。

また、全ての共訳者同士のレビューが完了した後、監訳のために新たな Pull Request を作る場合があります。
監訳によって共訳者の訳文を変更する場合があります。
単純な誤字訂正や用語の統一であれば共訳者に連絡のみしてマージする場合がありますが、構文の変更などより大きな見直しであれば共訳者に意見を求める場合があります。

### リリース

最終的なリリース形態の候補は Gitbook です。
Gitbook は、GitHub にある Markdown の原稿を参照し、ブラウザで読みやすいように提供するツールです。
[インナーソースパターン](https://patterns.innersourcecommons.org/v/ja/)も Gitbook で提供されています。

他の可能性として、[他の本のように](https://innersourcecommons.org/learn/books/) PDF を InnerSouce Commons のサイトで提供する方法も考えています。
章番号や参考文献を扱えるように、Markdown から Asciidoc や Sphinx などの形式へ変換する可能性があります。
やるとしてもプロジェクト終盤を想定しています。

## 日程

全員がこの分野の翻訳経験者であれば1ヶ月で終わるとも考えられますし、全員が初心者であれば2ヶ月以上かかるかもしれません。

始まりが10月中旬として11月末に完了する可能性が50%という目算は立てておきますが、締め切りを強制するものではありません。

## メンバー

@masskaneko

決まり次第記載します