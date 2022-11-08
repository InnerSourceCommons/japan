# 来客に良いハウスルールを作る: コントリビューション協定を書く

**概要**

* トラステッドコミッターには、コントリビューション協定の記述を通じてコントリビューターにハウスルール<sup>1</sup>を説明する責任があります(例えば、コード規約や依存関係等)。コントリビューション協定は生きたドキュメントです。
* コントリビューターは「良き来客」となり、コントリビューションの前にアグリーメントや他の目につくドキュメントを読む必要があります。コントリビューターが協定に沿って整ったコントリビューションをするほど、それが受け入れられるようになります。
* マネジメントはトラステッドコミッターがこれらのアグリーメントを作成することを支援する必要があります。
* アグリーメントを標準化することは、トラステッドコミッターのオーナーシップが低下することにつながるので慎重になる必要があります。複雑なアグリーメントはコントリビューションの妨げになるので、リスクの高いプロジェクトに限定されるべきです。

<!--
* Trusted Committers (TCs) are responsible for writing contributing agreements to explain house rules to contributors (e.g., code conventions and dependencies). Contributing agreements are living documents.
* Contributors need to be good houseguests and read the agreements (and any other findable documentation) before contributing. The better they groom their contribution to match the contributing agreement, the greater the velocity of acceptance.
* Management needs to support the TCs on these agreements.
* Be careful when standardizing agreements because this leads to less ownership by the TCs. Complex agreements can prevent contributions and should be reserved for high-risk projects.
-->

トラステッドコミッターは、壊れたコードや、適切にテストされていないコード、ドキュメントが書かれていないコード、彼らのコーディングスタイルから乖離したコードを受け入れ、オーナーシップを持たされることはできません。
コントリビューション協定は、それらの責務をコードを書いた開発者が担えるように形式化する方法なのです。
  
<!-- TCs cannot be forced to accept and take ownership of broken code, code without proper tests, undocumented code, or even code that doesn’t meet their style standards. Contributing agreements are a way to formalize the responsibilities of the developers on the originating side of the code. -->

- 訳注
  - 1: 一般にハウスルールとは、特定の団体や組織でのみ適用される規則を指しますが、この章では宿泊施設を比喩として持ち出し、プロジェクトのオーナーを宿主、コントリビューターを宿泊客、ハウスルールを宿泊規約と例えています。

## コントリビューション協定とは何か

トラステッドコミッターは、_コントリビューション協定_ を記述して所有します。
コントリビューション協定があることでハウスルールは明確になり、コードによるコントリビューションをトラステッドコミッターが受け入れるために必要なことをコントリビューターに知らせることができます。
コントリビューション協定は開発に携わるすべての人の目に触れられるものです。
アグリーメントには、トラステッドコミッターの名前や連絡先、スケジュールが記載されていなければなりません。
それ以外の内容はトラステッドコミッター次第ですが、以下の点が書かれていると良いでしょう。

<!-- The TCs write and own their _contributing agreements_. A contributing agreement is a device that specifies the house rules to let contributors know what is required in order for the TC to accept a code contribution. Contributing agreements are viewable by everyone in development. They must have the TCs’ names, contact information, and schedule. After that, the content is up to the TC. It will likely include some of the following: -->

* トラステッドコミッターの専門領域
* コミュニティ・ガイドライン
* コーディング規約
* テスト記述の規約
* ブランチ作成の規約
* コミットメッセージの規約
* 良いプルリクエストを作成する方法
* 機能リクエストの提出方法
* 不具合報告の提出方法
* セキュリティ上の問題の報告方法
* ドキュメントの書き方
* 完了の定義
* 依存関係
* ビルドプロセスの流れ
* スプリントの流れ
* ロードマップ

<!--
* The authoring TC’s specialties
* Community guidelines
* Code conventions
* Testing conventions
* Branching conventions
* Commit-message conventions
* Steps for creating good pull requests
* How to submit feature requests
* How to submit bug reports
* How to submit security issue reports
* How to write documentation
* Definition of done
* Dependencies
* Build-process schedule
* Sprint schedule
* Road map
-->

トラステッドコミッターは、プロジェクトを保護するためにこれらのアグリーメントを利用できるようにしておくことが重要です。
トラステッドコミッターは、もし他のチームによるコントリビューションが指定に従っていない場合、コントリビューション協定を参照しつつ、なぜコントリビューションが拒否されているかを説明できる必要があります。
そうすることは、社内政治や、より広範に渡る問題を最小化することに大いに役立ちます。

<!-- It is very important for the TCs to be able to invoke these agreements for protection. If another team’s code contribution does not meet the receiving TC’s specifications, the TC needs to be able to point to the contributing agreement to explain exactly why the code is being rejected. This helps immensely to minimize corporate politics and escalation issues. -->

## 私の家は君の家<sup>1</sup>

コントリビューション協定は、コントリビューターの期待値を管理するためにも重要な役割を果たします。
私たちは、宿泊客にとってのハウスルールを比喩として使います。
全員が同じ道徳規範に従っていると思い込むのではなく、宿主が宿泊客に自らの期待値を伝えれば物事はスムーズに進みます。
壊れやすいものがたくさんあり、整理整頓されたキッチンで普段から過ごす人と、程よい生活感のある部屋や猫の引っかき傷のある家具に囲まれて生活している人とでは、異なるハウスルールを持つことになるでしょう。

<!-- The contributing agreements are also crucial in managing a contributor’s expectations. The metaphor we use is that of house rules for guests. Everything goes more smoothly if hosts communicate their expectations to their guests, instead of assuming that everyone has the same standards. Someone with a nice house with many breakable things and a very organized kitchen will have different house rules from a person who lives in a comfortable mess with cat-scratched furniture. -->

そして宿主は、電子レンジと食器洗浄機を同時に動かそうとするとブレーカーが必ず落ちてしまうといったような、家の中にある予測のしづらい構造については予め客に注意を促さねばなりません。
コードに関するそのようなハウスルールや落とし穴を一覧化して配置するのに、コントリビューション協定は理想的な場所です。
そうすることで、それは明確に書かれたハウスルールのように、客が損害を被ったり、誤解をしたり、嫌な感情を覚えたりすることを未然に防ぎます。

<!-- And hosts should warn guests about quirks in their house, like a circuit breaker that trips if someone tries to run the microwave and the dishwasher at the same time. The contributing agreement is the perfect place to list the house rules and pitfalls of your codebase. And, like clearly explained house rules, it can prevent damage, misunderstandings, and hurt feelings. -->

ここまでの比喩は、コントリビューターの取るべき行動にも当てはまります。
善良な宿泊客は提示されたハウスルールに従いますし、当然のことながらルールにかかれていないことでも率先して整理整頓をするでしょう。
つまり、目についた不具合を回収したり、リファクタリングを施すこともあります。
そして _素晴らしい_ 宿泊客はボトルワインを持ってきてくれることもあるでしょう。
素晴らしいコードベースの「お客さん」は、新しい機能の開発にコントリビューションしてくれたり、誰もが待ち望んでいた修正をしてくれるかもしれません。

<!-- The metaphor extends to contributor behavior. Good guests follow the house rules, of course, but they also tidy up; that is, they help fix bugs or refactor code. And a _great_ guest brings a bottle of wine! A great codebase guest might contribute a feature or fix that everyone likes and wants. -->

- 訳注:
  - 1: 原文では "Mi casa Es Su Casa" と記載されています。これは直訳すると「私の家はあなたの家」ですが、転じて「気楽にしてね」という意味で使われます。

## ウィン-ウィン

多くのコントリビューターは、自分の行動や成果物がコントリビューション協定により従えば従うほど、それがより早く受け入れられコミットされると気づくでしょう。
また、より寛大なコントリビューション協定を見れば、変更を提案したり提出することのリスクはより低いとわかるでしょう。

<!-- Most contributors quickly realize that the more closely their submissions adhere to the contributing agreements, the faster those submissions are accepted and committed. Also, contributors know that when they see a more permissive agreement, there is less risk in submitting changes. -->

## 1つの解決策ですべてのサイズにフィットするか？

オープンソースの世界では、団体が異なればコントリビューションする際のルールも異なります。
違いのほとんどはリスクに関することです。
Linuxカーネルは、非常に厳しいコード提出のガイドラインや、単純なコントリビューション協定よりも遥かにプロセスを敷いています。
一方で、Node.js のモジュール開発は非常に寛大であり、プロジェクトに関わる人々には自分の作業が誰かの試みの重複になっていないかを検索を通じて確認するように求めている程度にとどまっています。

<!-- In the open source world, different groups have different rules for contributions. Most of the differences are risk related. The Linux kernel has very strict submittal guidelines and processes that go far beyond a simple contributing agreement. On the other hand, agreements for Node.js modules are very permissive; they mostly ask that people do a search to ensure that they aren’t duplicating someone else’s effort. -->

このような多様性が存在することは、ひとつの企業の中でいろいろなプロジェクトがあることと似ています。どんな企業でも、失敗すれば会社が傾いてしまうことが避けられない中核のプロジェクトがあり、そのプロジェクトには厳密なコントリビューション協定が求められます。
一方で標準化することが望まれるツールも存在し、これは比較するとかなりリスクの低い活動だと言えます。
そのツールを開発しているチームはよりシンプルなコントリビューション協定を敷き、人々がコントリビュートしてくれるように誘い出す柔軟さをもつべきでしょう。
しばしば、このようなリスクの低いコードベースはコントリビューターがインナーソースプロジェクトに参加する方法を学ぶのに安全な場所となるでしょう。

<!-- This diversity is very similar to the variety of projects in an enterprise. We all have certain core projects that could topple the business if they fail, and these projects require strict contributing agreements. But we also have tools that we would like to standardize, and this is a much lower-risk activity. The toolset teams should have the flexibility to have simpler contributing agreements to lure people into collaborating. Often, these less-risky codebases can be safe places for contributors to learn how to participate in InnerSource projects. -->

コントリビューションの作成では、安全性と参加しやすさのバランスが問われます。
短く簡単な協定はコントリビューションを歓迎していて、コントリビューションの過程で助言や支援をする意思があることを示すことになるでしょう。
長く、より複雑な協定はプロジェクトの難しさやリスクを伝え、そしてコードが受け入れいられるまでにコントリビューターはいくつかの関門をくぐり抜ける必要があるという事実を告げることになります。

<!-- Creating the contributing agreements is a balance between safety and participation. A short, easy agreement indicates that you welcome contributions and are willing to mentor people through the process of contributing. A longer, more complex agreement can convey difficulty, risk, and the fact that contributors need to pass several goals before their code will be accepted. -->

会社全体で標準化を進めて1つのコントリビューション協定を標準化しようと試みたことなる企業もあります。
これは大企業が無意識に取る行動としてはいたって自然なものです。
しかし、私たちはこの取組には反対してきました。
なぜなら、会社全体での協定はトラステッドコミッターからオーナーシップを取り上げることになり、それは彼らの同意を得ることが負担になるからです。
それは、これまで述べてきたような柔軟性を失うことにも繋がります。
代わりに、トラステッドコミッターのための出発地点として、様々なリスク水準や複雑さに適応できるコントリビューション協定の雛形を作成します。([「コントリビューション協定とは何か?」](#コントリビューション協定とは何か) にあるリストなどを記載します。)
また、私たちは、振り返りの後や、新しいトラステッドコミッターが加入したタイミングなどに、コントリビューション協定を読み返し必要な更新を加えるよう、トラステッドコミッターたちに依頼しています。
コントリビューション協定は生きたドキュメントであり続けることが不可欠なのです。

<!-- Some groups have tried to standardize one contributing agreement across the entire company. This is a pretty natural reflex for large enterprises. But we have fought against this because a company-wide agreement takes ownership away from the TCs, costing the company their buy-in, and eliminates the flexibility just outlined. Instead, we create templates as a starting place for TCs (such as the list in [“What Is a Contributing Agreement?”](#what-is-a-contributing-agreement)), adjusted for various levels of risk and complexity. We also ask that TCs revisit and update their contributing agreements after a retrospective or when new TCs are assigned to the codebase. It is vital that contributing agreements remain living documents. -->
