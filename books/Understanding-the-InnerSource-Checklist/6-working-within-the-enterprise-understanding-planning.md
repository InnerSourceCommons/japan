# 組織内にあてはめる: 計画の理解

<!--
* Transparency needs to be a part of the planning process. Creating internal transparency has led in our experience to more than an order of magnitude gain in external code acceptance.  
* Create formal processes to work within the enterprise environment. Formalizing processes keeps everyone on the same page.
* Transparency in planning helps because if the employees do not understand why decisions are made, they cannot propose corrections to the implementation. Top-down management is a complex process that rarely works. Open collaboration scales better.
-->
**要約**  
計画段階において、透明性はとても重要です。我々の経験上、組織内での透明性を確立することで、外部からのコード受入れ件数は桁違いの向上を見せる事がわかっています。
組織内での正式なプロセスを作成し、定型化することで、全員が同じ目線を持つことが可能になります。
もし仮に透明性が無く、意思決定の背景や理由を知らないようであれば、従業員はコードの修正提案を行う事ができなくなります。
トップダウンによるマネージメントは複雑で、めったに機能する事はありません。
オープンな共創こそスケールするのです。
  
<!-- The biggest difference between InnerSource and open source is the business structure and its constraints. Working within an enterprise means a constant pull of hierarchy and power structures that are often contrary to the basic ethos of transparency and individual agency that is key to open source. Yet, open source has much to offer the business world. So how do we adapt to the business environment without diluting the fundamental aspects of open source? -->
インナーソースとオープンソースの最大の違いは、企業における事業構造や制約に起因します。
企業の中では往々にして組織階層や権力が存在しますが、これらは透明性と個人の主体性を重んじるオープンソースの文化に反してしまいます。
一方で、ビジネスの世界ではオープンソースから学べる場合が多々あることも事実です。
では、どのように我々はオープンソースの基本的な文化を薄めることなく、企業内に応用していけばよいのでしょうか？

## 小さく、シンプルでありながらメンバーを巻き込む

<!-- Our biggest successes have resulted from finding and using a key point of leverage within the existing structures in the enterprise. We review current processes and find places to modify them in small ways to move incrementally toward InnerSource. We work with the business environment’s desire to work with _how_ s and not _why_ s, and simply tell them explicitly how to modify processes to improve outcomes, without going into lectures about transparency and ownership. It is best to make the changes as simple as possible, both to encourage adaptability and to avoid triggering the resistance large organizations can have to change. -->
私たちの最大の成功は、企業組織の中において既に存在している鍵となるような力を発見し、それをどう活用するかにありました。
現状のプロセスを見直し、それらをインナーソースに向けて小さく修正していくための方法を見つけるのです。
私たちは透明性や所有権について議論することなく、 _なぜ_ ではなく _どのように_ を考えながらビジネス環境の要望に応え、結果を改善するための明確な手段をシンプルに相手に伝えています。
適応性を高め、大きな組織が変化に対する拒絶反応を起こさないようにするためにも、変更は出来るかぎりシンプルにするのがベストです。

<!-- For example, our written process for creating contributor agreements is very small and simple with few requirements: the agreements are owned by the Trusted Committers (TCs), they are viewable by other teams, and they contain the TCs’ contact information and availability. Other than the contact information and schedule, we do not dictate the content of the agreements at all. Of course, we do encourage and expect them to contain much more information! And problems with a guest contributor become the ideal learning experience to trigger additions or changes to the contributing agreement. It’s kind of like when you stay at someone’s house, and the host has a rule of no loud music after 2 a.m.; you know that someone before you must have played loud music at 2 a.m. -->
例えば、私たちのコントリビューション協定を作成するためのプロセスは非常にシンプルで、要求事項はほとんどありません。
コントリビューション協定はトラステッドコミッターが所有し、他のチームからも閲覧が可能であり、トラステッドコミッターの連絡先や予定が書かれています。
むしろ、トラステッドコミッターの連絡先と予定以外には何も強要していません。
もちろん、他の情報も多く記載される事は推奨していますし期待しています!
ゲストコントリビューターが直面する問題は、コントリビューション協定の追加や変更を経験する理想的な学習体験になります。
これは誰かの家に泊まった時、その家の家主が深夜2時以降は音楽を大音量で流してはいけない、というルールがあるのと同程度です。

<!-- A crucial part of the TC process is that the employee who will be most affected by the change is given more power (and more responsibility) to manage that change. -->
トラステッドコミッターのプロセスで重要なのは、その変更の影響を最もうける従業員には、それを管理するためのより大きな権限を持つという事にあります。

<!-- These simple requirements, plus the rule that TCs are completely in charge of accepting or rejecting code changes, are relatively small and unalarming changes to the InnerSource process. But look at the results: -->
これらのシンプルな要求事項に加え、トラステッドコミッターがコードの変更を受け入れるか拒否するかのルールというのは、比較的小さいもので、インナーソースプロセスに対してあまり警戒されません。
しかし、こうした要求事項は次の結果につながるのです。

<!--
* The TCs have a huge incentive to fully participate in the new process.
* Better communication and documentation begins as soon as the agreement goes beyond contact information.
* The explicit expectations laid out in the document lead to better collaboration.
* Code changes move more quickly, leading to a positive feedback loop.
* As more code changes come in, the TCs do more mentoring, which creates more documentation.
* The TCs become more deeply familiar with their codebase and its external impact.
-->
* トラステッドコミッターには、新しいプロセスに関与するという大きなインセンティブが生まれます
* 協定に連絡先が掲載されていれば、すぐによいコミュニケーションとドキュメンテーションが始まります
* 明確に期待している事がドキュメントに書かれていれば、更に良いコラボレーションへつながります
* コードの変更は、更に迅速なポジティブフィードバックループへつながります
* 多くのコード変更を行い、トラステッドコミッターがより多くのメンタリングを行う事は、結果として多くのドキュメンテーションにつながります
* トラステッドコミッターは自分達のコードと外部への影響について更に深く理解する事になります
  
<!-- The minimal requirements allow the teams to adapt the process to their own needs—a major tenet of open source—and lead to the InnerSource goals of better collaboration, fewer bottlenecks, better integration, and, almost certainly, cleaner code. -->
要求事項を必要最低限に抑えることにより、チームのプロセスをチーム固有のニーズ（オープンソースの信念）に合わせることができます。
そして、良いコラボレーション、良いインテグレーション、ボトルネックの低減、整理されたコードというインナーソースの目標にもつながるのです。

<!-- ## Planning & Product Specialists -->
## 企画&製品スペシャリスト

<!-- After our success in improving integration with TCs and contributor agreements, we knew we had to create something similar to smooth the planning process. The product specialist role, which monitors all aspects of the product lifecycle, needs to work on breaking down silos between teams and products, and to see how these products can integrate with others in the company. -->
トラステッドコミッターとコントリビューション協定を活用しインテグレーションを加速させることに成功した後、製品を企画するプロセスにおいても同様の必要性を感じました。
製品のライフサイクルにおけるあらゆる側面を注視している製品スペシャリストは、チームや製品間のサイロをなくし、社内にある他の製品とインテグレーションできる方法を常に考える必要があります。

<!-- Product specialists need the ability and knowledge to properly negotiate and prioritize features across teams. But, we have found that even though people working on code or product integration _know_ they need to sit down and discuss things with the other teams involved, they don’t usually make time for the necessary meetings unless they’re pushed. Anything not on the schedule is easy to put off. This results in poor communication, delays, and misunderstandings. The fix is a formal process change to force the necessary meetings, with greater inclusion to ensure that the appropriate people are in the planning sessions, and greater transparency to break down the silo mentality. We are working with our product specialists now to improve public records of this process. -->
また製品スペシャリストは他チームと適切に交渉しつつ、実装すべきフィーチャーの優先順位を決める事ができる能力と知識が必要になります。
しかし、製品のコードや製品のインテグレーションに関わっている人でさえ本来は腰を据えて他のチームとじっくり議論しなければならないと _知っていつつも_ 強制されない限り時間を作らないものです。
元の予定に無かったものは、簡単に後回しになります。
その結果、コミュニケーション不足、遅延、誤解を生じさせます。
これを正すための手段は、正式なプロセスを変更し必要な会議を必ず開催すると同時に、適切な参加メンバーをより多く集め、透明性を高め、サイロ化された考え方をより多く壊していく事となります。
製品スペシャリストとは、このオープンなプロセスを改善するために協調しています。

## インクルージョンと透明性

<!-- Full inclusion in the planning stage of the process is crucial; all of the teams must be at the table for the process to work smoothly. Representatives from each team need to be present for the story grooming process, not just the owners of the primary codebase. Different teams often have different or conflicting priorities. Getting planners from each team together in one room helps them negotiate among themselves to get all the work done. Inclusion leads to smoother collaboration. -->
プロセスを円滑に進めていくためには、全てのチームが最初の企画段階から参加する事が不可欠となります。
ストーリーグルーミングのプロセスでは、主要なコードのオーナーだけでなく各チームの代表者が参加する必要があります。
ときにチーム間で優先順位は異なり、それらは相反することもあります。
各チームの企画者が集まることで、全てのタスクが完了するために何が必要か互いに話し合う事ができます。
インクルージョンによって協業は更に円滑になります。

<!-- Transparency during the planning process is also important. We feel that it helps to reduce conflict. When a conversation is public and intended to be archived, we find that participants often become better at considering the entire company when working out priorities. It helps to break down the silo mentality. -->
企画段階での透明性も同時に重要で、対立の減少に役立つと我々は考えています。
お互いの会話がパブリックな記録に残すつもりで行われると、参加者は全体によってより良い優先順位を考えられるようになる事を発見してきました。
つまり、サイロ化の考えに打ち勝てるという事です。

<!-- Transparency in planning increased as a side effect of adding more people to the planning meetings. More people are present for the trade-offs and negotiations. Just as important is the small process change we had already implemented, requiring that all relevant conversations be a part of the passive documentation. This means that everyone can review discussions in the future, and alters people’s conversational strategies. Also, by creating passive documentation, you can avoid information overload as people search more and spam less. -->
企画会議に参加する人数を増やした事で透明性が更に高まるという側面もあります。
トレードオフの議論をする場に、より多くの人が参加できるからです。
また、行った変更がたとえ小さなものだったとしても、関連するチーム同士の全ての会話をパッシブ・ドキュメンテーション(4章)として保存しておく事は非常に重要です。
これは、将来に渡り過去にどんな会話があったかをチェックする事ができると同時に、チーム同士の会話のあり方自体を変えるという事を意味します。
また、会話が自動的に保存されていくということは情報の過多を防ぎ、検索性を向上させ、スパムをへらすことにも繋がります。

<!-- Prioritization of projects and resources is usually done opaquely at companies. The reasoning is rarely made public and is done behind closed doors. This leaves employees to come up with their own narratives to explain priorities. Again, we see that when a company gives the _how_ but not the _why_, employees cannot make adjustments on the fly. It cripples their decision-making, and is a key element of bad escalation processes. -->
通常多くの企業では、プロジェクトやリソースをどう優先順位付けするかという議論を密室の中で行います。
そのため、従業員はその優先順位を説明するためには独自の物語を考えなければなりません。
ここでも _なぜするのか_ ではなく、 _どうするのか_ という事に焦点をあてなければ、その都度物語を考えさせられるはめになり、改善に向かえません。
不透明であるという事は、社員の意思決定のスピードを遅らせエスカレーションのプロセスも悪くなる要因となります。

<!-- Bringing transparency to the process gives employees the ability to make corrections as necessary, because they understand the end goal and will not blindly continue down a designated path that they know will lead to the wrong outcome. In addition, making prioritization and resource allocation more transparent reduces hierarchically based fears of kingdom building, or the appearance of it. -->
プロセスを透明化する事で、メンバーは必要に応じ軌道修正ができるようにもなります。なぜなら、本当のゴールを理解することで、誰かに指示されたものの間違った成果に繋がるやり方を妄信的に進むことがなくなるからです。
加えて、優先順位付けとリソース配置の透明性を高めることで、組織階層から生じる権威への不安や、実際にその権威の出現は少なくなります。

<!-- ## Planners Can Have an Impact on Processes -->
## 企画者はプロセスに影響を与えられる

<!-- We began with simple rules. For high-risk and high-demand codebases, we found it necessary to formalize planning. The product specialists worked with the TCs to add rules to the contributing agreements requiring external contributors to file an issue request before submitting a significant code change. “Significant” meant using more than three story points in Rally. This requirement was the first step in creating a solidified process that requires the product specialists on both teams to meet and collaborate with one another as well as the TC and contributor prior to a significant code change. -->
私達はシンプルなルールから着手しました。
リスクや需要が大きいコードベースでは、計画を形式化する必要があることがわかりました。
そこでプロダクトスペシャリストとTCが協力し、外部のコントリビューターが重要な変更を提出する際にはイシューリクエストの提出を義務付けるよう、コントリビューション協定にルールを追加しました。
ここでの"重要"とは、Rallyにおける３以上のストーリーポイントを使用する事を意味します。
このルールは、両チームの製品スペシャリスト同士、またコントリビューターとTCが協調する事を必須とする、強固なプロセス形成のための第一歩となりました。

<!-- Such structured meetings were not necessary for other codebases. Instead, their contributing agreements generally ask potential contributors to contact the TC and product specialist in advance on the listed discussion channels. Again, adaptability is key! -->
他のコードベースではこのような形式ばったミーティングは必要となりませんでした。
その代わり、決められたコミュニケーションチャネルの中で、潜在的なコントリビューターがTCと製品スペシャリストに事前に連絡しておくことをコントリビューション協定の中で定めています。
繰り返しになりますが、柔軟な適用性がキモとなるのです。

## ルールを定めた結果

<!-- Greater inclusion in the planning stages does create a resource problem initially: scheduling meetings with large groups is difficult, the meetings can run longer than anticipated, and every person pulled into a meeting necessarily is putting off other tasks. But we saw benefits almost immediately. The teams understood the prioritization process better, which improved our Agile process. And the change velocity in the core team’s ability to accept external code was so large that it more than made up for the time lost in planning, by a factor of 10. And we were able to clear stories from contributor’s teams that had been on the backlog for years. -->
計画段階から関連メンバを巻き込むことは最初はリソース上の問題を引き起こします。
たとえば、大勢のメンバーの都合のつく予定を見ながら会議を設定する事が難しかったり、会議自体が予想よりも長引く事もあります。
また、会議に参加しなければならないメンバーは他の業務を後回しにしがちです。
しかし私達はそれ以上の価値をすぐに理解しました。
チームメンバーは優先順位付けのプロセスを今まで以上に理解しはじめ、アジャイルプロセスの改善に活かされました。
一方でコアチームが外部からのコードを取り入れるスピードは非常に大きく改善されました。結果として、計画段階に費やされた時間の10倍以上を補填する事にまで繋がりました。
そして、何年もの間バックログに放置されていたコントリビューターチームの要望を完了する事ができたのです。

<!-- Opening up the process by including more people and making it more transparent also has an amazing effect on the teams’ ability to cross-collaborate. This leads to more effective decision-making both internally and across teams. We also found that by improving communication through passive documentation, eventually the meetings became smaller as teams used clearer communication. -->
より多くの人を巻き込んでプロセスを開かれたものにし、高い透明性を確保することは組織間のコラボレーションを行うにあたって非常に良い効果を発揮します。
これによって、チーム内・チーム間を問わずより効率的な意思決定が出来るようになりました。
また、パッシブ・ドキュメンテーションを徹底することによってコミュニケーションの質自体も改善し、結果として会議時間の縮小にも繋がる事もわかりました。

<!-- We did find that the increased communication required some external facilitation in the beginning. A key element was teaching the product specialists to negotiate more effectively by always looking at the win/win solution for the company. This stage was relatively short; after things were ironed out between teams, collaboration increased dramatically and little external help was needed. -->
初期において、コミュニケーションの増加は外部からのファシリテートが必要であることがわかりました。
重要なのは、会社にとってWin Winとなる解決策を常に模索し続け、より効果のあるコミュニケーションを製品スペシャリストに徹底してもらうよう働きかけた事です。
この期間は比較的短く終わりました。チーム間で物事が円滑に進むようになった後はコラボレーションが劇的に増加し、外部からの支援はほとんど必要がなくなりました。

<!-- ## Crossing the Gap from Planning to Developers -->
## 企画から開発者までのギャップを超える

<!-- To our great satisfaction, the teams at PayPal really began to work well together, doing some horse trading and some very complex bargaining. One team’s product specialist even came up with a new, simple process change that we have added to the InnerSource checklist: product specialists must create and own a file called _HELPWANTED.md_. This file is where product specialists can transparently post their backlog. Developers who are looking for a project to work on will search the code repositories, but don’t usually think to look into project management tools, even if they have access. So, the _HELPWANTED.md_ file is placed in the code repository. Again, findability is important! -->
私達の大きな目標を実現するために、PayPal 内のチームは抜け目がなく非常に複雑な交渉を共同で進めました。
ある製品スペシャリストは我々が実際にインナーソースチェックリストに追加した簡単なプロセス変更を考案しました。それは、製品スペシャリストは _HELPWANTED.md_ というファイルを自分たちで作成し、所有しなければならないというものです。
彼らは透明性を保ちつつ、このバックログをファイルの中に記載して掲載することができます。
通常、作業対象のコードリポジトリを探している開発者たちは、たとえアクセス権があったとしてもプロジェクト管理ツールの中まで調べようとは思いません。
よって、 _HELPWANTED.md_ をコードリポジトリに設置する事となるのです。
繰り返しますが、発見のしやすさは重要です。

<!-- Some well-done _HELPWANTED.md_ documents have been generated from the project management tools, complete with notes and levels of prioritization. This really helps inform guest contributors about other teams’ needs. Often, potential contributors can tell which stories are similar to their own projects, so they choose which ones they can help with the most. The _HELPWANTED.md_ file is a great addition to the win/win mentality. Contributors can and do trade with other teams, fixing an item in the backlog in exchange for moving their feature-sized code changes up the review list. -->
いくつかの良くできた _HELPWANTED.md_ は、ノートや優先順位付けのレベルも含め、プロジェクト管理ツールから生成されました。
これはゲストコントリビューターが他のチームが求めていることを知るのに大きく役立っています。
潜在的なコントリビューターは自分達の抱えているプロジェクトと近しいストーリーを見分けやすくなり、最もコントリビューションできそうなものを選びやすくなります。
_HELPWANTED.md_ は、Win/Winの精神に大きく寄与しています。
コントリビューターは他のチームのバックログの中にあるアイテムをこなす代わりに、自分達が追加したい変更をレビューリストの上位に移動するといった取引ができるようになりましたし、実際に行っています。
