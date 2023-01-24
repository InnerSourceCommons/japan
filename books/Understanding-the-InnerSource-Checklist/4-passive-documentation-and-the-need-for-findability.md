<!-- # Passive Documentation and the Need for Findability -->
# 検索可能性の必要性とパッシブ・ドキュメンテーション

**TL;DR**

<!--
* Passive documentation is crucial for mentoring and capturing tribal knowledge. The team takes a communication hit at the beginning, but the increase in velocity more than makes up for it.
* You can accelerate passive documentation by rewarding both the writers and consumers of the document.
* Passive documentation must be findable to be useable. Sometimes, this means that you will need to manually cross-tag between siloed datasets.
-->
パッシブ・ドキュメンテーションは部族内知識の捕捉と人材育成に欠かせないものです。チームは初期にコミュニケーションの落ち込みを感じることがありますが、速度の向上はその落ち込みを補っても余りあるのです。
ドキュメンテーションの作成者と消費者の両方に報酬を与えることで、パッシブ・ドキュメンテーションを促進することができます。
パッシブ・ドキュメンテーションを利用可能とするためには、それが検索可能な状態でなければなりません。ときどき、これはサイロ化したデータセット間のタグを手動で設定する必要があります。

<!-- Passive documentation is the record of the documentation we create every day while communicating openly. It is a great way to get tribal knowledge out of silos and into a format that is archival and findable. As an added bonus, it is typically kept with the project or the code that it documents, thus it is in an easy-to-find, context-relevant location. -->



<!-- ## Creating Passive Documentation -->
## パッシブ・ドキュメンテーションの作成

<!-- Passive documentation consists of written information that was produced not specifically to document for the future, but to explain something in the present, as it is needed. For example, it often includes the following: -->
パッシブ・ドキュメンテーションは将来のためではなく、現在必要なことを説明するために書かれた情報から成っています。
例えば以下のようなものです。

<!--
* Conversations that the Trusted Committers (TCs) have while mentoring a contributor who is learning how to integrate with her codebase
* Conversations the product owners have when they are explaining their priorities to one another, or arranging them
* The connection between a piece of the code and the project stories about the code, and the live conversations about both
-->
- トラステッドコミッター (TC) が、コントリビューターに対して、彼らのコードベースを統合する方法を指導する際に行われる会話
- プロダクトオーナーたちが互いにタスクの優先順位を説明したり、整理整頓するときに交わす会話
- コードの一部とプロジェクトのコードに関するストーリー、そしてこれらに関する生きた会話


<!-- At first, the most difficult part is persuading people to have these conversations more openly. They tend to start out wary of creating a lasting reference document on the fly. We found that when people realize that they are not writing formal documents, but are simply capturing mentoring conversations, the resistance dissipates. And the benefits of the rapid increase in documentation are quickly obvious to all. -->

最初に最も難しいのは、人々に対してこれらの会話をもっとオープンにすることを説得することです。
彼らは今後も参照するドキュメントを事前準備なしに作ることに対して慎重になる傾向があります。
しかし彼らが公式なドキュメントを書いているのではなく、単に育成のために交わした会話を記録しているだけであると気づくと、抵抗感がなくなっていくことがわかりました。
またドキュメンテーションの急速な拡充によるメリットは誰の目にも明らかでした。


<!-- To be captured in passive documentation, conversations need to happen in a written format. Common written formats include comments in a pull request, a tagged conversation in a public Slack channel, a comments page in a wiki, and a tagged email in a discussion group. In the open source world, we often say that conversations that don’t happen publicly on the email list or wiki aren’t “real.” We are working to change the culture internally to be the same. If there is an important discussion in person, at the end of it one person always commits to creating a written record of it. They do this by writing the discussion up in an email that all parties can approve, and then posting the write-up to the larger community. -->

パッシブ・ドキュメンテーションに記録されるには、会話は文書上で行われる必要があります。
一般的な記述形式はプルリクエストのコメント、Slack のパブリックチャンネルにあるタグ付けされた会話、wiki 内のコメントページ、ディスカッショングループ内のタグ付きメールなどです。
オープンソースの世界ではメーリングリスト、もしくは wiki で公開されていない会話は”本物”ではないとよく言われます。
私たちは社内においても同じような文化へ変化させていこうと取り組んでいます。
また、もし対面で重要な議論があったのであれば、最終的に誰か必ず一人が記録に残すことを約束します。
そのためには、全ての関係者が承認できるように議論の内容を詳しくメールに記述し、その内容をより大きなコミュニティにも公開します。


## “Did You Read the FINE Manual?”

<!-- We found that after the TCs had answered a few easy questions publicly on pull requests, the velocity of the next contributor’s pull request immediately increased. -->

トラステッドコミッターがプルリクエスト上で公開されたいくつかの質問に答えたあと、次のコントリビューターからのプルリクエストの速度がすぐに上昇することがわかりました。

<!-- Diligent contributors search the documentation before asking for help, or even writing their pull requests. In our case, we store this in GitHub, and because everything is in GitHub, there is little ambiguity about where to look. We encourage the TCs to refer contributors back to previous conversations when they do not incorporate previous advice in their pull requests. -->

勤勉なコントリビューターは助けを求める前に、あるいはプルリクエストを出す前にドキュメントを探します。
私たちの場合では、これらのドキュメントはすべて GitHub 上で管理しているのでどこを見ればいいかほとんど迷うことはありません。
またコントリビューターが過去のアドバイスをプルリクエストに反映していないとき、トラステッドコミッターたちに過去の会話を参照する様、差し戻すことをおすすめしています。

<!-- We are working on ways to reward these public conversations internally. We are creating dashboards that highlight when someone has written especially relevant documentation. And we allow TCs to reward contributors who do their research first. Trust me, the TCs will quickly learn who follows directions and will prioritize their pull requests first! -->

We are working on ways to reward these public conversations internally. 
社内の公開された会話を報いるための方法を探っています。

 We are creating dashboards that highlight when someone has written especially relevant documentation. 
特に誰かが関連のあるドキュメントを書いたときにそれを強調するダッシュボードを用意しています。

And we allow TCs to reward contributors who do their research first.
またトラステッドコミッターは最初に調査をしたコントリビューターに報酬を与えることができます。

Trust me, the TCs will quickly learn who follows directions and will prioritize their pull requests first!
トラステッドコミッターは素早く

## Findability
## ファインダビリティ

<!-- In the open source world, when you want to find out how to do something, you simply Google it. In the corporate world, finding information is much more difficult. Most information is locked away in different software and datastores that might or might not be searchable. Often the information in these applications is locked down by default, because that seems safer. But in the long run it is very damaging to a company. Locking information away makes onboarding a new employee a difficult process, and it makes integrating a new acquisition almost impossible. Moreover, it invites, or even encourages, an atmosphere of tribal knowledge. -->

オープンソースの世界では、何かをする方法について知りたいとき、単にググれば良いです。
しかし企業においては、情報を見つけることがオープンソースの世界と比較すると、はるかに難しいです。
たいていの情報は様々なソフトウェアやデータストアに保存され、検索可能かどうかもわかりません。
多くの場合、これらの保存先にある情報は、そうしておいたほうが安全そうということでデフォルトで広く公開されていない状態にあります。
しかしながら長い目で見るとこの状態は企業に大きなダメージを与えています。
情報を閉ざしてしまうと新しく入社した従業員のオンボーディングを困難なものにし、オンボーディングの際に習得できる知識の統一がほぼ不可能になります。
そのうえ、部族内知識を招く、あるいは助長する雰囲気を生み出しかねません。

<!-- Sometimes, those difficulties are created by the tools themselves when they have a bad or nonexistent search function. Sometimes, there are just so many tools being used that aggregation becomes an issue. Too often, problems are aggravated by pricing issues that force the company to shell out additional fees to enable access for all users. -->

時に、これらの問題はツール自身が持つ検索機能が粗悪だったり、そもそも存在しないことにより生じます。
ただ、多くのツールを使用しているので、情報の集約が難しいのです。
また、全てのユーザーがアクセスできるようにするためには、追加で費用がかかることが多く、この問題を悪化させているケースがよくあります。

<!-- But documentation is only useful if people can find it, so this is a really important problem to solve. Many of our teams have begun requiring cross-tagging spanning application silos in order to enable manual searching. For example, we have had several teams decide in their contributing agreement that they will not even consider a pull request that does not have a searchable tag of some sort, for example, a JIRA number for a bug fix, or a Rally story number for a feature-level pull request in GitHub. This is a huge help when someone needs to manually search across multiple locked-up datastores, but it isn’t ideal, and it requires developers to be quite diligent. -->

But documentation is only useful if people can find it, so this is a really important problem to solve.
しかしドキュメントが役に立つのは発見可能なときだけであるため、この問題の解決は非常に重要です。

Many of our teams have begun requiring cross-tagging spanning application silos in order to enable manual searching.
私たちのチームの多くは手動で検索ができるようにアプリケーションサイロをまたぐようにクロスタグの設定を要求するようになりました。

For example, we have had several teams decide in their contributing agreement that they will not even consider a pull request that does not have a searchable tag of some sort, for example, a JIRA number for a bug fix, or a Rally story number for a feature-level pull request in GitHub.
たとえば、
バグ修正のための JIRA の Issue 番号や、
GitHub の Feature レベルのプルリクエストに対する Rally Software® のストーリー番号、など
検索可能にするためのタグが設定されていないプルリクエストは考慮対象から外すとコントリビューション協定で定めているチームもあります。

 This is a huge help when someone needs to manually search across multiple locked-up datastores, but it isn’t ideal, and it requires developers to be quite diligent.
 これは誰かが閉ざされた複数のデータストアをまたいで検索する必要があるときに大きな助けになりますが、これは理想的ではなく、開発者たちがかなり勤勉であることが求められます。

<!-- We have begun creating tools to assist in finding and sharing information. We created (and open sourced!) [RallySlack](https://github.com/paypal/rallyslack). When someone is on Slack, RallySlack automatically pulls up all of that individual’s Rally stories to make it easier to find and tag a Slack conversation. With RallySlack, users don’t need to look up or memorize Rally story numbers. We are developing a similar tool for GitHub to help with tagging Rally story numbers in pull requests and issues. Eventually we hope to open source this tool, as well. -->

We have begun creating tools to assist in finding and sharing information.
私たちは情報の発見・共有を手助けするツールの開発を始めました。

We created (and open sourced!) [RallySlack](https://github.com/paypal/rallyslack).
それが [RallySlack](https://github.com/paypal/rallyslack) です（オープンソースです！）。

When someone is on Slack, RallySlack automatically pulls up all of that individual’s Rally stories to make it easier to find and tag a Slack conversation. 
誰かが Slack にいるとき、RallySlack は自動的に個々人の Rally ストーリーを収集し、検索と Slack での会話にタグ付けを簡単にしてくれます。

With RallySlack, users don’t need to look up or memorize Rally story numbers.
RallySlack を使えばユーザーは Rally のストーリー番号を探したり覚えたりする必要がなくなります。

We are developing a similar tool for GitHub to help with tagging Rally story numbers in pull requests and issues.
また、GitHub でのプルリクエストや Issue に対して Rally のストーリー番号のタグ付けを手助けする類似のツールを開発しています。

Eventually we hope to open source this tool, as well.
最終的にはこのツールも RallySlack 同様にオープンソース化したいと考えています。