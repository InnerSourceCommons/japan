# 最も重要な役割、そして最初の一歩: トラステッドコミッター

**TL;DR**

<!--
* For projects with any level of risk, you need to have a _Trusted Committer_. Define the role’s responsibilities clearly, based on the level of risk.
* Trusted Committers shift back and forth between coding and Trusted Committer responsibilities.
* The Trusted Committer role is difficult, and you need to reward those employees who deserve and accept the role.
* The rewards to the enterprise are great: better integrated code, better code reviews, faster pull request (PR) turnaround time, clearer knowledge for refactoring, more documentation with less pain, and bottleneck reduction.
-->
* リスクの程度に関わらずプロジェクトには _トラステッドコミッター_ が必要です。リスクの程度に応じ、ロールの責任を明確に定義してください。
* トラステッドコミッターはその役割への責任と同時にコーディングに対する責任も持ちます。その責任対象は行き来します。
* トラステッドコミッターは難しい役割なので、その役割にふさわしく、引き受ける社員には報酬を与える必要があります。
* 企業は、より統合されたコード、コードレビューの質向上、プルリクエスト応答時間の短縮、より明確なファクタリングのノウハウ、ドキュメント作成の省力化、ボトルネックの解消といった素晴らしい恩恵をうけます。

<!-- In the previous chapter, we described some of the cultural problems we’ve encountered. Codebase owners must accept pull requests, or they create bottlenecks and escalations up the management chain. External teams must learn and conform to the style and standards of the codebase to which they are contributing, or their contributions must be extensively rewritten. And when codebase owners and external contributors don’t work together, nothing gets better and everyone ends up discouraged. -->
前章では、私たちが直面したいくつかの文化的な問題を取り上げました。
コードの所有者はプルリクエストを受け付ける必要があります。そうしない場合ボトルネックとなり、上層部へのエスカレーションが発生します。
また、外部のチームはコードのスタイルと標準に準拠するべく学ぶ必要があります。そうしない場合はコントリビュートした内容を大幅に書き直さなければなりません。
コードの所有者と外部のコントリビューターが協力しなければ、何も改善されず、誰もががっかりすることになります。

<!-- Many of the problems stem from the fact that developers in the enterprise environment are often unwilling to dedicate time to reviewing and accepting pull requests or mentoring developers in other areas. And who can blame them? They typically have assigned tasks and goals that are specific to their own project, not to other projects that happen to touch their codebase. In addition, most people are disinclined to accept responsibility for something they have not written. -->
問題の多くは、企業における開発者が、プルリクエストのレビューや受け入れ、あるいはほかの領域の開発者の指導に時間を割くことを望まないことが多いことに起因しています。
ただ、それを責めることはできません。
一般的には、皆が自信にアサインされたタスクや目標を持っています。それは彼らのプロジェクトに対するものであり、たまたまコードベースに触れることになった誰かのプロジェクトに対するものではないのです。
そしてほとんどの人は、自分が書いていないコードに対して責任を負うことに抵抗があります。

<!-- But, for InnerSource to work, some developers _must_ take on responsibilities outside of their silos, so we created a new role with defined responsibilities and called it the Trusted Committer (TC). This is the most fundamental change we have implemented so far, and it is crucial to making InnerSource work. In fact, it is step one in its implementation. -->
しかし、インナーソースが機能するためには、一部の開発者がサイロの外に責任を負わなければ_なりません_。
そのため私たちは責任を定義した新しい役割を作成し、それをトラステッドコミッターと呼部ことにしました。
これは、私たちがこれまでに実施した最も基本的な変革であり、インナーソースを機能させるために不可欠なものです。
事実として、トラステッドコミッターを取り入れることはインナーソース実現への第一歩です。

## Defining the Role

<!-- The TC has the following list of responsibilities (each bullet point helps the TC’s team to better communicate and collaborate with other teams): -->
トラステッドコミッターには以下のような責任があります (各項目は、トラステッドコミッターのチームがより良いコミュニケーションと協業を実現するために役立ちます):

<!-- 
* Write and maintain the rules for contributing to the codebase
* Review incoming code (pull requests)
* Mentor contributors from other areas
* Merge pull requests
* Take the lead on refactoring and modularization
* Participate in discussion lists
* Send announcements
* Watch for and suggest opportunities for collaboration
-->
* コードベースへのコントリビューションに対するルール作成と管理
* 受け取るコード(プルリクエスト)のレビュー
* 他領域のコントリビューターへの助言
* プルリクエストのマージ
* リファクタリングやモジュール化作業のリーダーシップ
* ディスカッションリストへの参加
* アナウンスの発信
* コラボレーション機会の発見と提案

<!-- We should point out that in the open source world, many groups have independently evolved a similar role. We specifically borrowed from [“The Apache Way”](http://theapacheway.com), a tool developed by the [Apache Software Foundation](https://www.apache.org). These roles are assigned to people who have shown a high level of dedication to a project. TCs are ultimately responsible for the codebase, and are often gatekeepers of the code. The level of power in these roles often has a direct relationship to the amount of risk. For example, the Linux kernel is widespread and high risk, so the Linux kernel has divided its version of the TC role into two levels, Janitors and Mentors. On the other hand, Node.js modules are very low risk. The community might not embrace a new module after vetting it, but new modules can’t break anything, so there is no TC role. Anyone can publish a Node.js module with npm. -->

なお、オープンソースの世界では、多くのグループが独自に同様の役割を進化させていることを指摘しておきます。
私たちは特に、[Apache ソフトウェア財団](https://www.apache.org)が開発したツールである["The Apache Way"](http://theapacheway.com) を借用しています。
これらの役割は、プロジェクトに高いレベルの貢献をした人に与えられます。
トラステッドコミッターは、コードに対する最終的な責任を負っており、しばしばコードのゲートキーパーとなります。
これらの役割における力の程度は、しばしばリスクの大きさと直接的な関係があります。
例えば、Linuxカーネルは広範囲に渡っておりリスクが高いため、Linuxカーネルではトラステッドコミッターの役割を Janitors と Mentors のレベルに分けています。一方で Node.js のモジュールは非常にローリスクです。
コミュニティは精査後に新しいモジュールを受け入れないかもしれませんが、新しいモジュールが何かを壊すことはできません。そのためトラステッドコミッターの役割はありません。Node.js のモジュールは、誰でも npm で公開することができます。

## Refining the Role

<!-- After we had a defined role for the TC, we found a new problem: developers didn’t like the role, because they were afraid of getting too far away from the code; they didn’t want to lose coding time. They also struggled with prioritizing between coding and TC tasks. Plus, it was costly in time and attention for them to switch too frequently between those tasks. It made it difficult to get into the coding zone. To solve this issue, we considered removing programmers from active coding and assigning them the TC role as a full-time job. But this came with its own problem: we agreed that when people stop contributing code themselves, it becomes increasingly difficult for them to review code, especially integrations. Not to mention that it made programmers depressed because they would no longer be doing the kind of work they loved and entered the field to do. -->

さて、トラステッドコミッターの役割を定義した後、新たな問題が見つかりました。開発者はコードから引き離されてしまうことを恐れ、この役割を好まなかったのです。彼らはコーディングの時間を失いたくありませんでした。
また、彼らはコーディングとトラステッドコミッターのタスクの優先順位付けに苦労していました。
さらに、これらのタスクを頻繁に切り替えることは、時間と注意力の面でコストがかかりました。
コードを書くための集中モードに入ることが難しくなりました。
この問題を解決するため、プログラマーをアクティブなコーディング作業から外し、フルタイムの仕事としてトラステッドコミッターの役割をアサインすることを検討しました。
しかし、これには別の問題がありました。社員がコードのコントリビューションをしなくなると、コードレビューがますます難しくなってしまいました。特に統合作業においてはなおさらでした。
この業界に入った理由でもあるプログラミングにもう携われなくなるのですから、プログラマーが憂鬱になることは言うまでもありません。

<!-- Our solution is to have the TCs work with the product specialists to create a rotation schedule for themselves. They publish their schedules for other teams to see, in order to manage contributor expectations. We also find it helpful to list each TC’s specialties in the schedule so that the contributors know when someone with the appropriate expertise will be available to help them. It was also important to create new reward structures for the difficult and critical work done by TCs, a process I’ll describe later in the section “[Rewarding TCs](#rewarding-tcs).” -->
私たちの解決策は、トラステッドコミッターがプロダクトのスペシャリストと協力して、役割のローテーションスケジュールを作成することです。
コントリビューターの期待値を管理するため、他のチームが見ることができるようにスケジュールは公開されます。
また、スケジュールに各トラステッドコミッターの専門分野を記載しておくと、適切な専門知識を持った人がいつ支援できるかをコントリビューターが知ることができるようになります。
また、トラステッドコミッターが行う困難で重要な仕事に対して、新しい報酬体系を作ることも重要でした。
このプロセスについては、「[TCへの報酬](#rewarding-tcs)」のセクションで後ほど説明します。

<!-- In our experience, the number of TCs per project varies greatly. In a high-risk project with about 30 developers, we ask that six programmers be assigned to the TC role. At any one time, half of them actively work in the TC role, reviewing code and mentoring, while the other half actively code. They switch roles at the end of every two-week sprint. This has been ideal for the TCs, because two weeks is a good solid length of time to either really get into coding, or to settle into mentoring and documentation. -->
私たちの経験では、プロジェクトごとにトラステッドコミッターの人数は大きく異なります。
30人程度の開発者が参加する高リスクのプロジェクトでは、6人のプログラマーにトラステッドコミッターの役割を担ってもらうようにお願いしています。
常時、半分はトラステッドコミッターとしてコードのレビューや助言を行い、残りの半分は積極的にコードを書くようにしています。
2週間のスプリントごとにその役割は交代します。
これはトラステッドコミッターにとって理想的でした。
2週間という期間は、コーディングに没頭するにも、指導や文書作成に専念するにも、ちょうど良い長さだからです。

<!-- In our lower-risk projects like tooling, a single TC works on 10 repos or more. Most developers are very eager to mentor contributors on their toolsets. This is ideal for helping teams across enterprises figure out how to better standardize their toolsets because everyone is welcome to contribute. The main suggestion we have for those TCs is to have office hours so that they can maintain blocks of time to get (and stay) in the coding zone. -->
ツール開発のようなリスクの比較的低いプロジェクトでは、1人のトラステッドコミッターが10個以上のリポジトリで作業します。
ほとんどの開発者は、自分の開発したツールセットに関するコントリビューターへの助言にとても熱心です。
このようなツーリングには誰もが気軽に貢献できるため、企業全体のチームがツールセットをより適切に標準化する方法を見つけるのに理想的です。
これらのトラステッドコミッターに対する我々の主な提案は、コーディングに没頭し、その集中を維持するためのまとまった時間をもてるように、オフィスアワーを設けることです。

## Immediate Benefits

<!-- Assigning the code reviews of PRs<sup>[1](#annotation-1)</sup> to the TC role greatly accelerated the turnaround on the PRs and increased the level of code reviews. Plus, we found that TCs used their mentoring time to create some wonderful documentation for the next big refactor of code. The lead for one of the major architectural reworks said that using InnerSource helped his team really understand how to significantly refactor the codebase. It also greatly decreased the amount of interrupt-driven coding from external bug fixes because those were also addressed in the bug fix PRs. -->
プルリクエスト<sup>[1](#annotation-1)</sup> のコードレビューをトラステッドコミッターの役割に割り当てることで、プルリクエストのターンアラウンドが大幅に加速し、コードレビューのレベルも上がりました。
さらに、トラステッドコミッターはメンタリングの時間を使って、次の大きなリファクタリングに備えた素晴らしいドキュメントを作成することがわかりました。
とある主要なアーキテクチャの再構築に取り組んだ責任者は、インナーソースを使用することで、コードベースを大幅にリファクタリングする方法を、チームが本当の意味で理解するのに役立ったと述べています。
また、外部からの割り込みタスクとして入ってくるバグ修正に関しても、そのプルリクエストで対処されるようになり、大幅にコードの量が削減されました。

<!-- The documentation was created semi-painlessly by archiving public mentorship discussions between the TCs and contributors, and making them easily accessible in a context-relevant location in the codebase itself. This meant that the time spent on mentoring, valuable in and of itself, served double duty. We call this passive documentation, and we discuss it in more depth in [Chapter 4, _Passive Documentation and the Need for Findability_](/chapter-4#passive_documentation_and_the_need_for_f). -->
このドキュメントは、トラステッドコミッターとコントリビューターの間で行われた公開メンタリングの議論をアーカイブし、コードベースのコンテキストに応じた場所から簡単にアクセスできるようにすることで、ほとんど苦労せずに作成されました。
これは、メンタリングに費やされた価値のある時間が、二重の役割を果たしたことを意味します。
これをパッシブドキュメントと呼び、[Chapter 4, _Passive Documentation and the Need for Findability_](/chapter-4#passive_documentation_and_the_need_for_f)で詳しく説明します。

## Rewarding TCs

<!-- We found it important to work with HR and management to ensure the TC role is recognized formally. This solves two problems: development wins because they are reassured that management must respect the code review process, and no more Big Cheeses forcing code changes! The enterprise wins because the new role gives a path to promote programmers without taking them away from coding, which is what they do best and often love the most. -->
トラステッドコミッターの役割が正式に認識されるようにするには、人事部および経営陣と協力することが重要であることがわかりました。
そうすることにより、管理者がコードレビュープロセスを尊重する必要があることを再確認できるため、開発が成功しやすくなるほか、"お偉いさん" がコードの変更を強制することがなくなります。
この新しい役割は、プログラマーをコーディングから引き離すことなく昇進させる手段を提供するため、企業にとってもメリットがあります。

<!-- The TC role illuminates a developer’s advanced skills in mentoring, deep knowledge of architecture, and best code-review practices. We have found the TC role to be a difficult one, and companies need to determine how to properly reward those dedicated staff that take on the additional responsibilities. -->
トラステッドコミッターの役割は、開発者の高度なスキルを明確にします。
それはメンタリング、アーキテクチャに関する深い知識、コードレビューのベストプラクティスなど多岐にわたります。
トラステッドコミッターの役割が難しいものです。
そのため企業は、追加の責任を負う献身的なスタッフにどのように適切に報いるかを決定する必要があります。

<!-- We are enhancing our promotion path to Fellow for developers to reflect this complexity. This allows us to reward the “full-stack” developers we are creating and allows promotion without having to move to management roles that some developers find to be tedious. We get to keep the programmers that really understand the various codebases and encourage them to help refactor and reduce technical debt. -->
私たちはこのような複雑性を反映するために、開発者が "フェロー" に昇進するためのパスを強化しています。
これはフルスタックな開発者を生み出し、一部の開発者が退屈に感じる管理職に移行することなく昇進することにつながります。
そして、さまざまなコードベースを本質的に理解しているプログラマーを抱えることで、リファクタリングや技術的負債の削減に貢献することができるようになります。

<!-- <sup><span id="annotation-1">1</span></sup> GitHub uses the term PR, as do several other tools. Companies not using these tools might call the same thing problem reports, change requests, or tickets. -->
他のいくつかのツールと同様に GitHub はプルリクエストという言葉を使っています。
これらのツールを使用していない企業では、同じものを問題報告、変更要求、あるいはチケットと呼ぶかもしれません。
