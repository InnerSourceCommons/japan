<!-- 
# Why InnerSource?
-->
# なぜインナーソースなのか

<!-- 
A group of us in the open source community feel strongly that we can make work better by introducing and adopting open source principles and processes to larger enterprises.
This includes attributes that benefit the company (faster development, better cross-team collaboration, more documentation) and an ethos that benefits the workers (mentoring processes, accountability, and a supportive community).
-->
私たちはオープンソースコミュニティのグループの1つとして、オープンソースの原則とプロセスを企業に取り込むことで、もっとうまく仕事ができるようになると強く感じています。
この取り組みは、会社には開発スピードの向上やチーム間のコラボレーション向上、さらにはドキュメントの充実などの面で効果があります。また、従業員にはメンタリングや説明責任、コミュニティからの支援を通して職場の雰囲気が良くなるという効果があります。

<!-- 
It’s a big goal.
We started an organization called [InnerSource Commons](http://paypal.github.io/InnerSourceCommons/) to share information and ideas among organizations working with InnerSource.
We talk often about perfection being the enemy of action.
That’s one reason we focus on the smallest possible steps to effect change.
-->
これは大きなゴールです。
私たちは、組織の中で情報やアイデアを共有するインナーソースという枠組みを広めるために、 [InnerSource Commons](http://paypal.github.io/InnerSourceCommons/) というコミュニティを立ち上げました。
私たちは、まずは小さな変化を起こすことに焦点をあてています。
なぜなら、完璧を求めることは行動の妨げにしかならないからです。

<!--
At the Commons, we also believe that when companies fundamentally understand many of the methods of open source, they can be confident and productive actors in the open source community.
InnerSource is a way to bring them in while respecting their limits.
InnerSource opens teams and departments within a company, but does not release proprietary information.
It has been shown to be effective at reducing silos, increasing cross-stack understanding, and even stimulating innovation.
-->
Commons は、企業がオープンソースの基本的な枠組み理解すれば、自信をもってオープンソースコミュニティで生産的な活動ができると確信しています。
インナーソースは、誰もが各々の限界を尊重しつつ参加できる仕組みです。
インナーソースは、会社の中のチームや部門にオープンとはいえ、プロプライエタリな情報を公開するものではありません。
むしろ、サイロを減らして組織間の相互理解を深め、イノベーションを加速するのに効果的なものです。

<!--
In good open source tradition, we are writing this book to share some of what we in the InnerSource community are doing to bring open source tools and methodologies to the enterprise environment.
At the end, we present a checklist that quickly lays out the tasks that different parts of an organization have.
It also lets you see how far your organization has come in implementing an InnerSource project.
Our implementation of InnerSource adds common-sense steps as a recommended path, with a goal of “InnerSource-Ready” certification for groups completing the steps.
-->
どのようにオープンソースのツールや方法論を取り込んで、企業内にインナーソースコミュニティを立ち上げるか、その方法を共有するために、本書を執筆しています。
末尾には、組織の中ですぐに使えるチェックリストを掲載しています。
そのチェックリストを使えば、読者の組織がどの程度インナーソースプロジェクトの実装に近づいているかを確認できます。
インナーソースの実装としては、推奨する一般的なステップを記載しており、そのステップを完了したグループが「インナーソースの準備ができている」状態となることを目指しています。

<!--
The main point of this book is to find simple ways to encourage fundamental changes to typical corporate behavior.
-->
本書の目的は、典型的な企業活動の根本的な部分に変化を促す簡単な方法を見つけることにあります。

<!--
One of the great things about InnerSource is that it doesn’t need to begin—in fact, probably _should not_ begin—as a top-down mandate from headquarters.
Just one team in one department can make a few small changes in the right places to see results.
And, hopefully, other teams will be inspired enough to follow.
-->
インナーソースの優れた点の1つは、本社からのトップダウンの指示で開始する必要はないということです。また、開始すべきではありません。
ある部門の1つのチームが、その効果を確認するのに良い場所で小さな変化を起こすことができるものです。
そして願わくば、他のチームが刺激されて同じようにすることを期待しています。

<!--
Many InnerSource processes were born out of errors or problems.
In fact, one of our biggest strengths is our ability to learn from errors—those we make, and those that others make and then share.
Others will help us learn if we let them.
That’s one reason we encourage transparency.
-->
多くのインナーソースのプロセスは、エラーや問題を解決することから始まっています。
実際、私たちの最大の強みの1つは、自分や他人が犯した誤りから学んだ教訓を共有できることです。
私たちが教訓を共有することで、別の機会に他の人たちが助けてくれます。
これが透明性を奨励する理由の1つです。

<!-- For example, people working on product integration often find it easier to send a series of private email exchanges or hold meetings among a fraction of the people planning the integration than to bring all stakeholders into the process.
Requiring all of those involved to collaborate transparently has enormous payoffs,<sup><span id="annotation-1">1</span></sup> especially if you do it in a way that can be archived (in a discoverable location) so that other people can learn from it.
-->
例えば、製品のインテグレーション関わっている人たちは、一部の関係者だけでプライベートにメールをやり取りしたりミーティングをしたりする方が、すべてのステークホルダーを巻き込むよりも簡単だと感じています。
関係者全員に透明性のあるコラボレーションを要求し大きな効果を得る<sup>[1](#annotation-1)</sup>には、自らが率先して情報を(見つけられる場所に)置き、他の人が学べるようにすることが必要です。

<!--
InnerSource is enabled by tools and processes, but it is also a change to the culture.
The biggest change is allowing mistakes, talking about them, and learning from them.
-->
インナーソースは、ツールとプロセスがあれば実施できますが、文化の変化を起こすものでもあります。
最も大きな変化は、ミスを許して議論し、そこから学ぶことにあります。

<!--
This book is a true exercise within this premise.
We are putting it out in the open, rough edges and all, explaining lessons we’ve learned along the way, and sharing the solutions we have found.
It will be posted on the [InnerSource Commons site](http://www.innersourcecommons.org/checklist), where people can comment on it and help it grow.
We will print an official copy, of course.
But because we strive to live in the “Pull Request Culture” we are creating, if you’re reading the hardcopy and see anything wrong or feel the need to add more to the conversation, please contribute your feedback online.
-->
この本は、こうした前提のもと、実際に経験したことを元にして書かれています。
また、その経験から学んだことや解決方法を共有し、
誰でもコメントをしたり、その情報を参考に人々が成長できるように、 InnerSource Commons のサイトに全て公開しています。
さらに、公式コピーの出版もしています。
私たちは ”フルリクエストの文化” で活動するようにしているので、もしこのハードコピーを読んでいて間違いを見つけたり、議論を追加したりする必要があると感じたときには、いつでもオンラインでフィードバックしてください。

<!--
We understand that it can be difficult in a business environment to share feedback freely when _faux pas_ in brand management have financial repercussions.
At the Commons, we work under _Chatham House Rules_ (see the section “[A Brief History of InnerSource](#a-brief-history-of-innersource)” later in this chapter) so that people can feel confident that nobody is reporting on their involvement until they are ready to go public.
Likewise, with this book we have changed some names to protect the innocent, so to speak.
-->
ビジネス環境においては、自由にフィードバックを共有することがブランド価値を低下させ金銭的な影響を生じる可能性があることから、難しいこともあるでしょう。
Commons は、チャタムハウス・ルール(この章の後ろにある “[インナーソースの歴史](#a-brief-history-of-innersource)”を参照)で活動しているので、明示的に公開を許可しない限り、誰もあなたの関与について触れません。
実際、この本でも関わった人を守るために、何人かの名前を変更しています。

<!--
We hope that as we go on this journey, you will see how taking advantage of small changes can begin to make larger cultural change a reality.
And, yes, some serious change management techniques are proposed here.
-->
この本に書かれていることを実践したことで起こる小さな変化が、より大きな文化の変化へと繋がることを体験していただきたいと考えています。
そのために大切なマネージメント技術の変更がここで提案されています。

<!-- 
## Our Audience
-->
## 対象読者

<!--
We strive to include something for everyone in this book.
Developers can learn what it’s like to be either a contributor or a _Trusted Committer_ (more on this role a bit later) who vets the contributions.
Product owners and product specialists can make large gains through reuse, collaboration, and integrations.
Planners will better understand how to manage the changes that InnerSource brings and will learn how helping teams negotiate the complexities of integration and collaboration can reduce tribal knowledge and technical debt.
And, finally, upper management will find new ways to improve employee satisfaction and to integrate new business units and acquisitions.
-->
この本は、全ての読者がそれぞれの立場について学ぶことができるように書かれています。
開発者は、コントリビュータや、コントリビューションされた内容を確認する _トラステッド・コミッター_ (この役割については後ほど説明します)が、どのようなものが学べます。
プロダクトオーナーやプロダクトスペシャリストは、再利用やコラボレーション、インテグレーションを通して、大きな効果が得られます。
プランナーは、インナーソースの導入による変革をどのように管理するか理解することで、複雑なインテグレーションやコラボレーションを調停したり、属人的な知識や技術的な負債を減らせるようになります。
そして最後に上位の管理者は、従業員満足度を向上したり、新しい事業ユニットや買収した企業を統合するための、新しい方法を発見できます。

<!--
## What Does Open Source Have That I Don’t Have?
-->
## オープンソースにあって私にないものは何か

<!--
Briefly, open source has flexibility, synergy across groups because of transparency, a culture that fosters collaboration, and a combination of standardization and easy-to-find documentation that greatly improves the learning curve.
Open source has developers that participate due to intrinsic motivations, an ethos of honoring mentors, and a view of contributions as a gift, not a burden.
Transparency and widespread contributions lead to software that better meets the needs of the users.
-->
端的に言うと、オープンソースには柔軟性があり、透過性に基づくグループ間の相乗効果があり、コラボレーションを推奨するカルチャーがあり、そして標準化され簡単に見つけられるドキュメントを用いることで学習曲線を大幅に改善しているという特徴があります。
オープンソースには、メンターに対する敬意を持ち、コントリビューションを負担と考えずにギフトと考えて自発的に参加する開発者がいます。
透明性や広範なコントリビューションで、より多くのユーザのニーズが満たされるようになっています。

<!--
## Open Source Today
-->
## 今日のオープンソース

<!--
Open source software has “won.” Every _Fortune 500_ company uses or works on some kind of open source project.
Sonatype, a major player in the open source community, conducted a survey in 2014 of large enterprises and found that “more than 90 percent of a typical application is now open source components.”<sup><span id="annotation-2">2</span></sup>
One major advantage of open source software is that it has consistently shown a lower defect density than the industry average.<sup>[3](#annotation-3)</sup>
-->
オープンソース・ソフトウェアは、「勝利した」と言われています。
Fortune500に掲載されている会社は、何らかのオープンソースプロジェクトを利用したり、そこで活動したりしています。
オープンソースコミュニティにおける主要なプレイヤーである Sonatype は、2014に大企業を対象に行った調査で「今や典型的なアプリケーションの90％以上がオープンソースコンポーネントとなっている」ということを明らかにしました。<sup>[2](#annotation-2)</sup>
オープンソース・ソフトウェアの主な強みのひとつに、欠陥密度が産業界の平均よりも一貫して低いということがあります。<sup>[3](#annotation-3)</sup>

<!--
## Open Source’s Future in the Commercial World: InnerSource
-->
## 産業界におけるオープンソースの将来：インナーソース

<!--
But how do the strengths of open source help _within_ a company? Realistically, most companies cannot be strictly open source, because regulatory and commercial requirements forbid them from sharing their source code.
This is where InnerSource comes in.
InnerSource is a method of applying lessons learned in the open source software movement to companies that are developing software internally.
-->
しかし、 _企業内_ でオープンソースの力はどのように役に立つのでしょうか。
現実的には、ほとんどの企業が、規制や契約上ソースコード共有が禁止されているなどの理由で、オープンソースの力を活かすことができていません。
ここでインナーソースの出番となります。
インナーソースは、オープンソース・ソフトウェアの活動から学ぶことを、企業内のソフトウェア開発に活かす方法なのです。

<!--
InnerSource can help corporations become better actors in the open source community, while bringing the advantages of open source to the corporate world.
Our most important goals are the following:
-->
インナーソースはオープンソースの利点を企業文化に取り入れることで、企業がオープンソースコミュニティでより良い活動者となるのに役立ちます。
その重要なゴールには、次のものがあります。

<!--
* To help the enterprise learn how to improve collaboration
* To help the enterprise create cleaner code
* To reduce bottlenecks
* To facilitate integrations between teams
-->
* 企業内のコラボレーション改善方法を学ぶ
* 企業内で洗練されたコードの作成を促進する
* ボトルネックを減らす
* チーム間連携を促進する

<!--
In most enterprises, it is difficult to make significant changes quickly.
Even when it’s possible, rapid cultural or process change can be more disruptive than helpful.
This goes double for when the changes are mandated from the top without buy-in from the people in the trenches.
InnerSource works by starting with the smallest steps possible to effect change, and by making meaningful compromises to adapt to circumstances.
This minimizes disruption and gives people a chance to see how effective it is before making larger steps.
In fact, just a single team in one department can effectively adopt InnerSource.
-->
大きな変革を素早く起こすことは、ほとんどの企業にとって大変困難なことです。
急激な企業文化やプロセスを変更は、状況を改善させるのではなく、悪化させてしまうことがあります。
これがトップからの強要で、関係者からの賛同が得られない場合はなおさらです。
インナーソースの仕組みをうまく機能させるためには、効果測定しやすい小さな活動から始め、状況に応じて折り合いをつけながら柔軟に進めることが重要です。
こうすることで、大きな変革を起こす前にインナーソースはどのような効果があるか関係者が理解でき、混乱を最小にできます。
実際に、ある部門の１チームからインナーソースを始めるのが効果的です。

<span id="a-brief-history-of-innersource"></span>
<!--
## A Brief History of InnerSource
-->
## A Brief History of インナーソース

<!-- Deciding to apply open source methodologies on an enterprise level is neither new nor unique.
Many people have worked on similar projects for almost as long as open source has existed.
It is a natural decision because so many people enjoy working on open source projects and want to bring that ethos into their work environment.
Many names have been used to describe this process of translating open source to the enterprise, from “internal open source,” “enterprise open source,” and “visual source” to “corporate open source,” but few have succeeded for long.
The term we are using was coined by Tim O’Reilly more than 15 years ago.
Originally, it was “Inner Source,” but we removed the space between the words so that the term is findable in a search.
-->

<!-- 
InnerSource as a movement or method began with a conversation among a group of us in the open source community who were independently working to bring the open source ethos to the commercial world.
We created a consortium in true open source fashion[4](/chapter-1#fn05) to create and maintain InnerSource definitions and standards.
This way, open source leaders are able to maintain the ethos and culture of the true meaning of InnerSource, even in the sometimes-difficult enterprise environment.
One key element of this process has been our fervent adoption of _Chatham House Rule_:
-->

<!-- 
> When a meeting, or part thereof, is held under the [Chatham House Rule](https://www.chathamhouse.org/about/chatham-house-rule), participants are free to use the information received, but neither the identity nor the affiliation of the speaker(s), nor that of any other participant, may be revealed.
-->

<!--
The simplicity of the Chatham House Rule embodies what we are working toward with InnerSource.
Creating simple rules that are easy to follow gives us maximum leverage to effect change.
Transparency in a commercial environment has been a huge hurdle.
This rule addresses commercial enterprises’ fear of collaboration with potential competitors and allows us to be more open with one another about what we are trying to do.
It allows us to admit our failures and to share information and complaints with our peers so that we can work together as a group to quickly solve our problems.
-->

<!--
The Chatham House Rules are a compromise that open source did not need to make to survive, but that has been crucial to InnerSource’s creation and growth.
It is pleasingly symbolic that we are using this tool of transparency and openness—along with a crucial dose of privacy—to create our new definition of InnerSource.
It perfectly illustrates the dichotomy we are balancing.
-->

## What Lies Behind Open Source Practices

<!--
A long tradition of jokes and humorous stories show children or unsophisticated people acting out things that they’ve seen other people do—for instance, building a nonfunctional plane from bamboo in a [cargo cult](https://en.wikipedia.org/wiki/Cargo_cult)—without knowing why.
The humor springs from the absurdity of actions taken out of the original context where they made sense.
Unfortunately, too many practices adopted by businesses from open source projects fail for the same lack of understanding.
What makes it even more difficult to adopt open source practices intelligently is that many open source practitioners talk about them enthusiastically without understanding why they worked in the open source setting.
-->

<!-- 
Most business documents stress _how_ to do things, but not  _why_ .
Business environments often move too quickly to solidify processes.
This report lays out the  _why_ s so that you set up the right environment in which your new practices are likely to succeed.
We put the checklist for starting InnerSource at the end of the report because we first want to give context and human stories, showing you why we came up with the processes we did.
Bringing InnerSource to enterprises is a complex undertaking, and what we did might not work for everyone else.
We prefer to explain why we decided we need a new rule and  _why_  a process works for us so that you can create your process—your own _how_—to fit your needs.
-->

<!--
Of course, you can skip to the checklist in this book or at this [book’s website](http://paypal.github.io/InnerSourceCommons/) if you’re eager to move on.
But we’ve made it easy to skim the  _why_ s: Each chapter begins with a TL;DR (Too Long; Didn’t Read) that sums up a problem we found, the smallest possible step to move toward a solution, and why that solution works.
-->

<!--
<sup><span id="annotation-1">1</span></sup> More on this in [Chapter 6](/chapter-6#working_within_the_enterprise_understand).
<sup><span id="annotation-2">2</span></sup> Wayne Jackson, [“The 2014 Survey: Marked by an Industry Shock Wave”](http://bit.ly/2o3vRR6), The Nexus, June 20, 2014.
<sup><span id="annotation-3">3</span></sup> In Coverity’s annual static code analysis reports, most recently, the [“Coverity Scan Report”](http://bit.ly/2o3g7O6).
<sup><span id="annotation-4">4</span></sup> Specifically, Apache Software Foundation style.
-->
