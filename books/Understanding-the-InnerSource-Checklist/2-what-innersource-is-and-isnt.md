# インナーソースとは何なのか？何ではないのか？

<!-- **TL;DR** Too often, enterprise culture wants to change the definition of InnerSource to something more familiar. We must help enterprise stakeholders create clear practices and definitions in order to maintain the culture of open source as much as possible while still highlighting the benefits to the enterprise. -->
**TL;DR**  
企業では、インナーソースを身近に感じられるように定義しようとすることがよくあります。
本章では、インナーソースおよびそのプラクティスを明確に定義できるように解説していきます。
営利企業としての利益に焦点を当てつつも、オープンソースの文化を受け入れられるような定義が必要なのです。

<!-- One of the major problems we have encountered when implementing InnerSource has been, at its root, a vocabulary problem. After we completed several successful InnerSource projects, we noticed that many people began using the word InnerSource in a simplistic, degenerate manner. Probably the most damaging misunderstanding was that InnerSource meant outsourcing work from a busy team to another that presumably had more capacity. In general, it’s easy to fall into the fallacy of thinking that effective processes are just about following certain procedures or using certain tools, without regard for the culture that makes success possible. -->
インナーソースの実践において筆者が経験してきた最も典型的かつ根源的な問題は、語彙の問題です。
筆者らがインナーソース適用のプロジェクトをいくつか終えた後に気づいたのは、適用先の社員がインナーソースという言葉を矮小化して使い始めたことでした。
最も深刻な痛手は、インナーソースという活動が忙しいチームの手を離れて別のチームに割り振られた外注的な作業であるという誤解です。
成功のための文化を考えようとせず、決まった作業手順に従おうとしたり特定のツールを使ったりすると、良いプロセスであっても簡単に失敗するのです。

<!-- Discussing the problems caused by this vocabulary issue became a bonding moment for all of us at the InnerSource Commons. Many members of the Commons want to focus on the larger problems of culture change, and the distorted definitions of Innersource were emblematic of the problems they are fighting. InnerSource goes much farther than simple processes or tools, and sometimes that makes definitions more difficult to communicate in an enterprise environment. -->
こうした語彙の問題はインナーソースコモンズ全員の結束をうながすものとなりました。
多くのメンバーは、文化の刷新という大きな問題に挑戦したいと考えており、インナーソースに対する歪んだ理解は戦う相手の筆頭だったのです。
インナーソースは単純なプロセスやツールよりも上位の概念であり、企業に定義を浸透させてゆくのは難しいのです。

<!-- The vocabulary issue might sound minor, but we’ve found again and again that it is vital, especially when introducing change, that terms are clearly and explicitly defined and agreed upon. It is also important that the definitions are easy to find. This includes terms like “InnerSource,” but also includes roles and responsibilities. Some of the first steps toward InnerSource are to clearly and publicly define standards, roles, and responsibilities. -->
語彙の問題というと小さく聞こえる読者もいるかもしれません。
ですが、用語を明確かつ厳格に定義して合意することが変革には不可欠であることを、我々は何度も痛感してきました。
また、定義はすぐに確認できるものでなければなりません。
インナーソースの定義だけでなく、そのための組織標準、職種、責任といった定義が明確かつ組織全体に示されている必要があるのです。

## GitHub を使ってるからインナーソースはできてるでしょ？

<!-- **TL;DR** GitHub helps with code transparency, but doesn’t actually change the typical enterprise silo-based mentality. Without the processes we talk about in this book, GitHub instead creates serious collaboration and integration issues, which can turn into bottlenecks, especially on critical codebases needed by many teams. -->
GitHub は組織におけるコードの透明性を上げますが、それだけで組織の縦割り問題が解決するわけではありません。
本書で扱うプロセスがなければ、GitHub が協働やインテグレーションの深刻な問題を引き起こします。
また、そうした問題は、たくさんのチームが依存する中心的なコードベースにおけるボトルネックになりかねないのです。

<!-- The idea that GitHub is all that’s needed to be InnerSource is a concept we fight against daily. Most people do not realize that it takes much more than GitHub to find, create, and grow open source communities. The communities create the software, not the other way around, but more often than not, large companies lack a sense of holistic community. -->
インナーソースの実現には GitHub が必要だという意見は、私達が毎日戦っている概念です。
ほとんどの人々は、社内におけるオープンソースの源を見つけ、コミュニティとして育ててゆく方が GitHub の活用よりもはるかに大変であることに気づいていません。
コミュニティがソフトウェアを作るのであって他の何者でもないのですが、大企業にはそれに気づくためのコミュニティ全般に対するセンスがないのです。

### インナーソースは文化とプロセスであり、ツールだけではない

<!-- The first steps toward InnerSource must be to foster trust and increase clear communication. This makes it possible for a sense of community to grow and improves collaboration. But businesses often lead from the _how_, rather than the _why_. We can’t tell them to foster trust in their teams; that is too vague and can’t be expressed as an action item. We fight the constant battle of process and hierarchy versus agility and customer influence. So how do we work around that? How do we make better decisions and collaborate more, without spending more money? These are things that GitHub cannot answer but InnerSource can. -->
インナーソースを実現する初歩は、信頼を育むことと明確なコミュニケーションを増やすことです。
これにより、新たな協働を引き起こして改善してゆくためのセンスを磨く機会が生まれるのです。
従来のビジネスでは _なぜか？_ よりも _どうやって？_ に着目しがちであることに注意しましょう。
チームの信頼を育むというのは漠然としていて、具体的な作業内容を定義することはできません。
ですから、プロセスと組織的階層 vs アジリティと顧客の影響という対立が生まれるのです。
さて、どうすれば我々は良い意思決定と多くの協働をコストを抑えて実現できるでしょうか？
これこそがインナーソースにできて GitHub にはできないことなのです。

<!-- It is true that using a tool like GitHub to make version control easy, visible, and accessible is a step in the right direction. But we need to think beyond tools and their advantages and flaws, and consider people. Enterprises are made of people with their own fears, habits, established patterns, hierarchy, and motivations, and they respond to corporate politics as much as to technology. This is why each of the checklist items focuses on some aspect of the human piece of the puzzle. -->
GitHub のようなバージョン管理とコード検索のツールを使うこと自体は、インナーソースの実現に向けた正しい方向です。
ですが、ツールの良し悪しよりも人を考慮する必要があります。
企業とは、人々の不安、習慣、定型作業、階層、意志によって形作られているものであり、技術よりも社内の政治的力学によって動いているのです。
本書の終わりに示すチェックリストが人に関連するものとなっている理由はこれなのです。

### GitHub はあるがインナーソースではなかったとしたら

<!-- The first big problem we encountered when introducing InnerSource was an increase in escalation up the management chain. We like to call it the “Big Cheese Story” (see the following sidebar). At its core, it is a story of fear. We believe it is unique to the corporate environment and not the open source world. We found that this story resonated with many of our participants in the InnerSource Commons. The awesome part is that open source’s existing processes already had several pieces of the solution, though they had not been put together before. -->
筆者らがインナーソースの導入時に最初に直面した大きな問題は、マネジメント層で報告が増えることでした。
筆者らはこの問題を "お偉いさんの物語" と呼ぶことにしました。
可愛らしい名前ですが、恐怖の物語です。
願わくば企業の中だけで起きることであり、決してオープンソースの世界で起きてほしくはないことです。
インナーソースコモンズのメンバーからの報告では、この問題はあちこちの企業で起きていることがわかりました。
そして、素晴らしいことにオープンソースのプロセスでは、この問題を解決する鍵がいくつか既にあるということです。
ただ、企業では見つけていなかったのです。
一体どういう意味なのか、"お偉いさんの物語" をもとに理解していきましょう。

<!-- Once upon a time, there was a company that decided to embrace InnerSource, so it dictated that all code was to be moved to GitHub Enterprise. Because there was no cohesive version control before, there was much rejoicing across the company. Now, the developers finally had visibility to one another’s code! No longer would the developers need to submit a change request to planning, and hope it was accepted and scheduled some time in the next year. Visions of seamless collaborations danced in developers’ heads! -->
あるとき、インナーソースを始めた会社がありました。
インナーソースなのですから、全てのコードを GitHub に移すことにしました。
それ以前は統一的なバージョン管理の仕組みが無かったので、社内ではあちこちから歓喜の声が上がりました。
ついに他の開発者のコードを見ることができるようになったのです！
何か変更を提案するときに、それが受け入れられ、来年のいつかに計画され、なんていう首を長くする時間とはおさらばなのです。
開発者達は円滑な協働のできる未来を想像して浮足立っていました。

<!-- An intrepid programmer decided to do a pull request on the big codebase, and told her manager that she could write the necessary change in a matter of weeks. Her Big Cheese was very pleased. So, the intrepid programmer wrote the change and submitted the pull requests and waited...and waited...and waited...until her Big Cheese became very unhappy and asked why the changes had not been added. The intrepid programmer replied that she had finished the work and submitted the pull request, but the changes hadn’t been accepted by the other codebase. -->
ある勇敢なプログラマーは大きなコードベースに対してプルリクエストを送ると決め、上司に「数週間で書ける」と報告しました。
彼女のお偉いさんはとても喜び、彼女はついにプルリクエストを送りました。
そして、待てど…暮らせど…一向にマージされません。
とうとうお偉いさんの機嫌は悪くなり、なぜ変更されないのか勇敢なプログラマーに問い詰めました。
彼女は「自分の仕事は終えてプルリクエストを送ったのですが、一向に受け入れられないのです。」と答えました。

<!-- So, her Big Cheese went to the Big Cheese that owned the other codebase, and asked him to force one of his groups to accept those changes. After all, there was now a big backlog waiting to go through! The Big Cheese of the codebase agreed and ordered some poor individual in his group to accept those changes. But that individual didn’t like how the intrepid programmer wrote the changes, because they were not “how things are done.” They were written in a different style, used a different test scheme, and maybe didn’t take advantage of an existing module. Thus, the second programmer rewrote the entire change before adding it to the codebase. -->
そこで、彼女のお偉いさんは別のコードベースを統括するお偉いさんを訪ねました。
そのコードベースを担う組織の1グループに、変更を受け入れてもらうように強く願い出たのです。
なにしろ他に仕事が山積みなのですから！
そのコードベースのお偉いさんは提案に同意し、グループ内の冴えないプログラマーに変更を受け入れるよう命じました。
ところが冴えないプログラマーは勇敢なプログラマーのコードが気に入りませんでした。
自分流の書き方ではないからです。
コーディングスタイルも違うし、テストの仕組みも違うし、既存のモジュールも活用していないようでした。
結局し、冴えないプログラマーは提案されたほとんどのコードを書き直してからコードベースに取り込む羽目になりました。

<!-- No one learned anything. No documentation was created. And now everyone hates InnerSource because it creates bottlenecks and makes programmers look difficult to the Big Cheeses. Plus, the product owners are frustrated because no one has included them in the process. -->
色々と苦労があったにも関わらず、誰も何も学びませんでしたし、何のドキュメントも作られませんでした。
インナーソースは手間がかかるし、お偉いさんの印象も良くないからダメだ、と皆が感じるようになっていきました。
また、プロダクトオーナーは自分を通さずに物事が進むのにイライラしていました。

<!-- ### Breaking Down the Big Cheese Problem -->
### お偉いさん問題の詳細

<!-- At first, we were surprised by the Big Cheese problem, because we knew that the more code that other teams can see into, the better they can understand the pieces they are integrating with and/or reusing. But we found that just having the code visible doesn’t automatically lead to collaboration, especially in an enterprise environment. The incentives are different from the open source environment. -->
インナーソースの適用プロジェクトを始めた頃はお偉いさん問題に驚かされました。
他チームのコードを見ることができれば、それらをどのように自チームのコードと統合したり、あるいは自チームのために再利用したりできるかに役立つと考えていたからです。
しかし、単にコードが見えるだけでは協働にはつながらないということがわかりました。
特に大企業であるほどこの問題は顕著です。
オープンソースの世界とは利害の力学が違うのです。

<!-- First, most of the code had previously been developed in silos. This meant that teams had undocumented styles, structures, and practices that outsiders couldn’t know about until they submitted code that could not be accepted by the maintainers. Beyond that, there was a siloed culture that encouraged people to talk only to people in their own group and to use language that outsiders couldn’t understand. This often happens in complex structures. I’ll cover the organizational aspects later in this booklet. -->
まず、ほとんどのコードは閉じた部署(サイロ)の中で開発されていたことに注意が必要です。
つまり、部署の構造も業務プロセスも習慣も明文化されておらず、部外者は知るよしもないのです。
ですから、部外者がコードの変更を提案しても受け入れられなかったのです。
それだけではありません。
部署では内部の社員とだけ話し、部外者には通じない言葉を使う文化がありました。
これは複合的な構造の組織ではよくあることであり、後述します。

<!-- If you do not understand the underlying architecture of the full stack, especially an older one with poor documentation, making silos is a normal response. It is easier to understand and take ownership of only your component. This is the piece you have the most control over. However, this method doesn’t lend itself to an atmosphere of collaboration, and can increase complexity and discourage reuse. -->
ソフトウェアのアーキテクチャを理解していない開発者がいたとして、特にそのソフトウェアが古いものでドキュメントに乏しい場合、その開発者が特定の集団に閉じこもろうとするのは自然なことです。
自分達の理解できるコンポーネントのみに責任を持つ方が簡単であり、コントロールし続けられるからです。
しかし、それでは協働しようという雰囲気にはならず、アーキテクチャは複雑になり、コンポーネントは再利用されなくなってしまうのです。

<!-- Because of this complexity, potential collaborators didn’t want to contribute until the pain from lack of integration was more painful than the fear of contributing. And the owners of the codebase were loath to accept responsibility for code that was not their priority and was written by someone not on their team. This resistance to collaboration resulted in a constant stream of escalations up the leadership chain. It turned GitHub into a bottleneck, especially for high-demand codebases, which tend to be high risk. Consequently, the code that the most people needed access to became the most difficult to contribute to. -->
コントリビューションをしたいと思っている開発者であっても複雑さの前に恐れてしまい、本当に協力しないとまずいという切羽詰まった段階になるまで踏み切ろうとしないのです。
また、コードベースの責任者は、自チームではない開発者が書いたコードに対する優先度を低く見積もり、責任を受け入れることを嫌がりました。
こうした協働への反作用が、上司になんとかしてもらうという連鎖を生みました。
そして、需要の高いコードベースであるほど GitHub がボトルネックになってしまいます。
結局、最も多くの人がアクセスするコードが、最もコントリビューションしにくいコードになってしまうのです。

<!-- We found that contributors were often inspired to write pull requests for the changes they needed in other codebases. But the codebase hosts were not accepting their pull requests, mainly because it meant extra work and responsibility for them. It became all risk and little gain. -->

<!-- We had to go back in the history of open source to find answers to these cultural problems. Then, we had to figure out how to make the solutions match enterprise structures. And we had to simplify the solutions so that they could be more universally adopted. I’ll explain our solution in [Chapter 3, _The Most Important Role, and the First Step: Trusted Committer_](/chapter-3#the_most_important_rolecomma_and_the_fir). -->

### More Communication Pitfalls

<!-- Communication in a siloed culture presents problems that are very different from those in a traditional open source environment. In particular, planning is significantly different. Two weeks before the beginning of my employment at PayPal, several teams submitted their feature-level integration requests to one popular codebase as a part of their quarterly planning. The core team took those stories and rewrote them to fit the current construct of their codebase, with no involvement of the submitters, and then sent them back to the external teams. Near the end of the quarter, many team leads came to the InnerSource team with the rewritten stories, complaining that InnerSource was really just “conscripted code.” They felt like they were being conscripted to do another team’s work. They did not realize that the code they were being asked to produce was actually the changes needed to complete their own integration requests. Confused, we sent them back their original requests and showed how the new stories were actually derived from their original stories. This is when we learned that the external teams had not been involved at all in the rewrite. Clearly, this was a major communication failure! For the next (and all subsequent) rounds of planning, we made sure all teams were present for the negotiations and rewrites of stories. After this communication problem was solved, we made significant gains. An order of magnitude of code was accepted through pull requests, and external stories that had been on backlogs for years were cleared. -->

<!-- We also had an issue with teams creating significant pull requests against codebases with little to no warning to the codebase owners. Of course, in an enterprise environment, such a significant expenditure of resources without planning or communication too often became a battle of the Big Cheeses. -->

<!-- We needed to create a defined list of proven practices based on our experiences. We could see that better communication and well-defined expectations across teams was absolutely necessary. [Chapter 6, _Working Within the Enterprise: Understanding Planning_](/chapter-6#working_within_the_enterprise_understand) presents an explanation of the steps we’ve taken toward a solution. -->
