# Appendix

## 実際のチェックリスト

<!-- It’s easy to feel overwhelmed with the task of starting an InnerSource project, much less taking your organization through the transition to a true InnerSource or open source company. PayPal has drawn a checklist from its own experiences and the experiences of colleagues in other companies making the transition. We present it here to help organize and focus what you need to do. Certainly, following the checklist slavishly will not produce success. Every organization needs to undertake investigations, discussions, and cultural change in order to benefit from InnerSource. But keeping this checklist in front of you can help reassure you that you’re making progress. -->
InnerSource プロジェクトを開始する事に対してプレッシャーを感じるのはその通りで、ましてや、真の InnerSource またはオープンソース企業への移行を通じて、あなたの組織をかじ取りをするのは簡単ではありません。PayPal社は、独自の経験と移行を行っているほかの企業の同僚の経験からチェックリストを記載しています。私たちは、あなたが何をすべきかを整理し、集中するのに役立つよう、ここにチェックリストを提示します。もちろん、このチェックリストに素直に従うだけでは、成功は得られません。全ての組織は、調査、議論、InnerSource の恩恵を得るための文化的に変化することを始めていく必要があります。しかし、あなたがこのチェックリストを常に確認していれば、進捗があることがわかり安心するでしょう。

<!-- This report was inspired by both the GNU Manifesto and Checklist Manifesto. We hope to inspire you to take at least a small step toward InnerSource and creating your own checklist and sharing it with us. The Apache Way was an important inspiration for the team, and you will spot similarities in this list. -->
この文書は、GNUマニュフェストとチェックリストマニュフェストの両方に触発されたものです。私たちはあなたがInnerSourceにむけて少なくとも小さな一歩を踏み出し、あなた自身のチェックリストを作成し、それを私たちにも共有(展開)してくれることを期待しています。Apache Wayはチームにとって重要なインスピレーションであり、あなたもこのリストに同じような感覚を感じることでしょう。

<!-- 
* Readiness
  * Personal
    * Do you believe this is a viable strategy for your company, or are you just doing it out of ideological commitment and idealism?
    * Do you understand the changes required to be successful at InnerSource?
    * Are you skillful at presenting ideas to others, listening to their concerns, and finding common ground without bias?
  * Project
    * Does this project matter to the company? Is it likely to survive strategy changes?
    * Appropriateness
      * Is this project likely to be interesting to developers outside the original development team?
        * Is it currently or could it be used widely by other teams in the company who depend on it?
        * Will it benefit from being extended by outsiders in ways that the original team could not anticipate?
      * Could the project benefit from having other teams contribute bug fixes and refactoring work?
      * Could outside developers contribute useful code or suggestions?
      * Would outside developers respond to appeals to contribute?
    * Code maturity
      * Is the project modular enough to make changes easy and safe to make?
      * Is the code well documented?
    * Existing process
      * Can releases be made frequently?
      * Is continuous testing and integration in place?
      * Is all of the code stored in a version control repository such as GitHub that makes branches, pull requests, and integration easy?
  * Team
    * Are team members ready for the challenges of InnerSource?
      * Accepting code and changes to their code from outsiders
      * Being responsible for less-than-perfect code contributed by outsiders
      * Having outsiders see their less-than-perfect code
      * Having to conduct conversations that are sometimes difficult with outsiders about accepting and rejecting their contributions
      * Mentoring and/or learning to mentor contributors
    * Do team members understand the requirements of running an InnerSource project? (It helps if members have participated on open source projects.)
      * Creating and maintaining documentation for guest contributors
      * Willingness to participate in forums and answer questions patiently
      * Using forums, which provide a historical record everyone can see, instead of hallway conversations (optionally, using a scribe to make notes during live meetings, just as long as all of the decisions and explanations for those decisions are documented)
      * Willingness to do code reviews of outside submissions
      * Maintaining the bug tracker
      * Taking a turn in the role of TC
    * Have you chosen TCs?
      * Do they understand their responsibilities?
        * Write and maintain the _CONTRIBUTING.md_ file in GitHub
        * Review incoming code (pull requests)
        * Mentor guest contributors
        * Merge pull requests
        * Take the lead on refactoring and modularization
        * Participate and answer questions on discussion lists
        * Send announcements
        * Watch for and suggest opportunities for collaboration
      * Do they understand the potential rewards (intrinsic and job-related) of this position?
        * Develop deeper understanding of the codebase
        * Improve the quality of your team’s code
        * Improve the quality of code within the organization as a whole with better integrations
        * Learn and grow as a developer by seeing many incoming code examples
        * Understand how to better refactor and modularize code to encourage external contributions
        * Develop interpersonal and leadership skills through mentoring and negotiation with guest contributors
      * Have they been given leeway to do things not previously in their job descriptions?
    * Is time set aside in team members’ work schedules for these new responsibilities?
    * Are team members trained to handle these responsibilities?
    * Is there a mechanism for making announcements that anyone in the organization can follow and search? (Examples: Slack, email)
    * Is there a recorded mechanism for discussion so that all Guest Contributor questions and internal team decisions are searchable by incoming Guest Contributors? (Examples: Slack, online forum)
  * Company
    * CxO-level executives
      * Do the executives understand the purpose and value of running a project as InnerSource?
        * The value of spreading tribal knowledge across the organization
        * The value of having teams remove their own external blockers and bottlenecks
        * The value of a more interconnected organization
        * The value of having advanced team members that have a deeper understanding of many arms of the codebase
        * How InnerSource encourages basic good practice and helps develop and spread even better coding and development practices
        * How InnerSource increases the learning and development of individual developers
      * Are they willing to support flexible work requirements and time spent on cross-departmental contributions?
      * Can they accept experimentation, failure, and repositioning?
      * Are they willing to support a path for career advancement that does not require management?
      * Does the executive team support the initiative?
      * Are company goals and KPIs clearly stated and shared?
      * Are the company’s vision and mission relevant, up-to-date, clear, respected, and followed?
    * Human resources
      * Are there rewards and criteria for promotions based on InnerSource values?
        * Rewards for people who contribute to projects in other departments
        * Rewards for developers who handle contributions from other departments (TCs)
      * Need path for advancement that respects community role and does not require moving into management
    * Organizational setup
      * Central coordinating team
        * Is the team set up?
        * Is it ready to communicate with projects interested in going InnerSource? Can it apply the criteria in this checklist to ensure that the project and team are ready?
        * How do projects register as InnerSource?
      * Do staff members have time to contribute to outside projects?
      * Do staff members have resources to measure and demonstrate gains and losses of teams?
      * Can staff members choose what projects to work on based on their expertise and motivations?
      * Is there a meritocratic philosophy that can appreciate good contributions from all corners?
    * Developers
      * Do developers around the company understand that they can contribute to the InnerSource project?
      * Do they understand the value of contributing to other projects?
        * Removing external blockers
        * Building integrations with other tools themselves
        * Seeing how other teams structure code and learn from examples
      * Do they understand the process for making contributions to other projects?
        * Joining the discussion
        * Reading the contribution requirements
        * Exploring and/or contributing to the Help Wanted file
        * Signing up for announcements
      * Do they know how to use the tools?
        * Version control
        * Programming language
        * Test development
      * Do they know how to support their team’s role in InnerSource?
        * Can they participate productively on forums?
          * Answer contributor questions
          * Describe the reasons for choices that have been made in a way that is clear
          * Respond constructively to feedback
        * Can they participate in dialogs around reviews of their code?
      * Are they permitted to contribute to projects outside their departments?
        * Do they understand how to get support from their product owners and managers?
* Repository
  * Are ancillary resources set up, such as the following?
    * Documentation
    * Discussion forum
    * Bug tracker
    * Wiki
  * Are the following files in place?
    * _README.md_
      * Project name
      * Any earlier names and codenames for this project
      * Project description
      * Team lead and PM/PMO contact information
      * Keywords for search purposes
        * So that people can find this particular project by name
        * So that people can find this project by what it does
      * How to sign up for the announcement list
      * Location of discussion forum
      * Location of other repositories (Examples: JIRA, Rally, Confluence)
    * _CONTRIBUTING.md_
      * Required
        * Table of contents
        * Names and contact information for TCs
        * TC availability schedule
      * Optional
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
        * Dependencies
        * Build process schedule
        * Sprint schedule
        * Road map
        * Helpful links, information, and documentation
        * When the repositories will be closed to contributions
    * _HELPWANTED.md_
      * Can be initially empty
      * Can link to a forum where requests and offers are posted
      * Can contain a list of requests and offers
    * _GETTINGSTARTED.md_
      * Whatever a contributor might need to get the app up and running to begin coding
      * Can be filled in by an intern, or after some contributors get started, based on feedback about what would have been helpful to them to get started
  * Who reviews the documents in the repository?
* Tools
  * Version control
  * Continuous integration
  * Testing
* Logistics
  * Sprints
  * Codeathons, especially for tools
  * Education
  * Testing
  * Gamification
  * Reporting
    * Pull requests during recent period
      * Number
      * Size (in lines of code)
      * Type
      * Name of pull request submitter
    * Baseline metrics
    * Ongoing tracking
      * Resources
        * Costs
      * Time
    * Who sees measurements? Display to the community?
  * Bug fixing
* Product owners 
-->
* 準備
  * 個人
    * これが会社にとって実行可能な戦略と思っていますか？それとも、観念的な誓約と理想論から抜け出そうと活動していますか？ +
    * InnerSourceで成功するために必要な変化を理解していますか？ +
    * あなたは、他人にアイデアを提示したり、相手の心配事に耳を傾けたり、偏りのない共通点を見つけたりするのが得意ですか？ +
  * プロジェクト
    * このプロジェクトは会社にとって重要ですか？戦略変更を受け入れられそうですか？
    * 妥当性
      * このプロジェクトは、オリジナルの開発チーム以外の開発者にも興味をもってもらえそうですか？
        * それは今時点で社内の他のチームが依存するほど広く使われている、もしくは広く使われそうですか？
        * オリジナルチームが予想できなかったような形で、他の開発者による拡張によって利益を受け入れることができますか？
      * 他のチームがバグ修正やリファクタリング作業によって貢献することで、プロジェクトはその利益を受け入れることができますか？
      * 他チームの開発者が有用なコードや提案を提供してくれますか？
      * 他チームの開発者が貢献の要請に応えてくれますか？
    * コードの成熟度
      * プロジェクトは簡単にかつ安全に変更が行えるよう十分なモジュール化がされていますか？
      * コードは十分にドキュメントがそろっていますか？
    * 既存の工程
      * リリースを頻繁に行うことができますか？
      * 継続的なテストや統合が行われていますか？
      * 全てのコードがGitHubのようなバージョン管理リポジトリに登録されており、ブランチやプルリクエスト、マージが簡単にできるようになっていますか？
  * チーム
    * チームメンバーがInnerSourceの課題に挑戦する準備ができていますか？
      * 他チームの開発者からのコードやコード変更を受け入れられますか？
      * 他チームの開発者が投稿した完ぺきではないコードに責任を持てますか？
      * あまり完ぺきとは言えないコードを見てもらえる他チームの開発者がいますか？
      * 他チームの開発者の貢献の受け入れや拒否について、それらが時々困難であり会議しなければなりません
      * 貢献者への助言し、助言できるようになるよう学べますか？
    * チームメンバーはInnerSourceプロジェクトを実行するための要件を理解していますか？(メンバーがオープンソースプロジェクトに参加したことがあると望ましい)
      * ゲスト貢献者のためのドキュメントの作成・保守
      * フォーラムに参加する意思、根気強く質問に回答する意思
      * 廊下での会話の代わりに、誰もが見ることができる履歴付きのフォーラムの使用(オプションで、ミーティング最中にノートをとることができ、全ての決定とその説明が文書化される)
      * 外部からの提出物のコードレビュを行う意思
      * バグトラッカーのメンテナンス
      * Trusted Committer の役目を交代できる
    * Trusted Committer を選択したことがありますか？
      * 彼らは自分たちの責任を理解していますか？
        * GitHubのCONTRIBUTING.mdファイルに名前を書き、保守する
        * 投稿されたコードのレビュ(プルリクエスト対応)
        * ゲスト貢献者への助言
        * プルリクエストのマージ
        * モジュール化とリファクタリングを率先して実施
        * 議論リストを使った質問の共有と回答
        * お知らせ・告知
        * 連携の機会を見極めと提案
      * 彼らはこのポジションへの潜在的(内在的・仕事関連)な報酬を理解していますか？
        * コードベースへの理解度を深める
        * あなたのチームのコード品質を改善する
        * より良い統合により、組織内のコード品質が全体的に改善する
        * 多くの投稿されたコードサンプルを見ることにより、開発者として学び成長する
        * 外部からの貢献を促進するためのコードのリファクタリングやモジュール化の方法を理解する
        * ゲスト貢献者への助言や交渉を通じて、対人能力やリーダシップ能力を養う
      * これまでの職務内容に無いことをするための余裕が与えられていますか？
    * チームメンバの仕事のスケジュールには、これら新しい責任のための時間が確保されていますか？
    * チームメンバーはこれら責任を履行するための訓練を受けていますか？
    * 組織内の誰もがフォローしたり、検索したりできるようなアナウンスの仕組みがありますか？(例：Slack, E-mail)
    * 全てのゲスト貢献者からの質問やチーム内の決定事項が新たなゲスト貢献者から検索できるように、議論を記録しておける仕組みがありますか？(例:Slack, オンラインフォーラム)
  * 企業
    * 経営層 (CxOレベル)
      * 幹部はInnerSourceとしてプロジェクトを運営する目的と価値について理解していますか？
        * 組織全体に*民族的な知識*を広めていく価値
        * 独自に抱えている拒絶意識やボトルネックを取り除くチームを持つ価値
        * より相互に繋がった組織の価値
        * コードベースの多くの機能をより深く理解している高度なチームメンバーを持つことの価値
        * InnerSourceが、基本的な優れたプラクティスを推奨し、さらに優れたコーディング&開発プラクティスの形成と浸透支援をどの程度行うか
        * InnerSourceが個々の開発者の学習と開発力をどの程度育てるか
      * 幹部は柔軟な仕事の要件や部門を超えた貢献に費やされる時間を喜んでサポートしていますか？
      * 幹部は実験、失敗、再配置を受け入れることができますか？
      * 幹部はマネージメントを必要としないキャリアアップのための道筋を喜んでサポートしていますか？
      * 経営層は、このイニシアチブを支持していますか？
      * 会社の目標とKPIが明確に示され、共有されていますか？
      * 会社のビジョンとミッションには関連性があり、最新のものであり、明確であり、尊重され、守られていますか？
    * 人事部
      * InnerSourceの価値観に基づいた昇進のための補修や基準がありますか？
        * 他部門のプロジェクトに貢献した人への報酬(制度)
        * 他部門からの貢献を担当した人への報酬(制度)
      * コミュニティの役割を尊重し、管理職への昇進を必要としない昇進の道筋が必要
    * 組織体制
      * 中心で調整してくれるチーム
        * チームの準備が整っていますか？
        * InnerSourceに興味を持っているプロジェクトとコミュニケーションをとる準備ができていますか？
         そのプロジェクトとチームの準備ができているかをこのチェックリストの基準に評価できますか？
        * どのようにプロジェクトをInnerSourceとして登録しますか？
      * スタッフメンバーは外部プロジェクトに貢献する時間がありますか？
      * スタッフメンバーはチームの損益の計測と実証を行うリソースが割り当てられていますか？
      * スタッフメンバーは自身の専門性やモチベーションに基づいてどのプロジェクトに取り組むかを選ぶことができますか？
      * 様々な方向からの優れた貢献を評価できる実力主義の理念がありますか？
    * 開発者
      * "会社関連のある"開発者たちは、InnerSourceプロジェクトへ貢献できることを理解していますか？
      * その開発者たちは他のプロジェクトへ貢献することの価値を理解していますか？
        * 外的妨害要因の除去
        * 他のツールとの統合を自ら構築すること
        * 他のチームがどのようにコードを構築しているか例を通じて学ぶこと
      * その開発者たちは他のプロジェクトへ貢献するためのプロセスを理解していますか？
        * 議論への参加
        * 貢献するためのルールの閲覧
        * "FAQ/要望ファイル"の閲覧や記入
        * 告知への署名
      * その開発者たちはツールの使い方を知っていますか？
        * バージョン管理システム
        * プログラミング言語
        * テスト開発用ツール
      * その開発者たちは、InnerSourceにおける自分たちのチームの役割をサポートする方法を知っていますか？
        * その開発者たちは、生産的にフォーラムに参加できますか？
          * 貢献者からの質問への回答
          * その方法を選択した理由の明確な説明
          * フィードバックに対する建設的な対応
        * その開発者たちは、自分たちのコードのレビューに関する意見交換会に参加できますか？
      * その開発者たちは自部署以外のプロジェクトへ貢献することが許可されていますか？
        * その開発者たちは自分たちのプロダクトオーナーやマネージャからサポートを得る方法を理解していますか？
* リポジトリ
  * リポジトリに紐づいて、下のような"補助的なリソース"がセットアップされていますか？
    * ドキュメント
    * 議論用のフォーラム
    * バグトラッカー
    * Wiki
  * 以下のファイルが置かれていますか？
    * README.md
      * プロジェクト名
      * このプロジェクトの以前の名前やコードネーム
      * プロジェクトの説明
      * チームリーダーのプロジェクトマネージメント(組織)の連絡先
      * 検索目的のキーワード
        * 人々がこのプロジェクトを名前で検索できるように
        * 人々がこのプロジェクトをやっていることで検索できるように
      * 告知リストへの登録方法
      * 議論用のフォーラムのURL
      * 他関連リポジトリ(例:JIRA, Rally, Confluence)のURL
    * CONTRIBUTING.md (貢献について.md)
      * 必須
        * 目次
        * Trusted Committer の名前と連絡先
        * Trusted Committer の利用可能なスケジュール
      * 任意
        * コミュニティガイドライン
        * コーディング規約
        * テスト規約
        * ブランチ作成規約
        * コミットメッセージ規約
        * 良いプルリクエストを作成するためのステップ
        * 機能リクエストの提出方法
        * バグレポートの提出方法
        * セキュリティレポートの提出方法
        * ドキュメントの書き方
        * 依存関係情報
        * (自動)ビルドプロセスのスケジュール
        * スプリントスケジュール
        * ロードマップ
        * 有益なリンク，情報，ドキュメント
        * リポジトリのクローズタイミング
    * HELPWANTED.md (FAQ/要望ファイル.md)
      * 最初は空っぽでも可
      * 要望や提案が投稿されたフォーラムとリンクを張ることが可能
      * 要望や提案のリストを含むことが可能
    * GETTINGSTARTED.md "(入門書)"
      * 貢献者がアプリを立ち上げてコーディングを開始するまでに必要なステップ全て
      * インターンシップ生のような初心者や初めて貢献された方たちが、始めるにあたって自分にとって役に立ったであろうことについてのフィードバックに基づいて、記入が可能
  * 誰がリポジトリのドキュメントをレビューしますか？
* ソフトウェアツール・システム
  * バージョン管理システム
  * 継続的統合システム
  * 試験ツール、試験システム
* プロジェクト実施の計画
  * スプリント
  * コードアソン[コーディングに特化したハッカソン] 特にツール関連
  * 教育
  * 試験
  * ゲーミフィケーション[参加者の意欲をかき立てる手法]
  * レポート作成
    * 直近のプルリクエストの
      * 総数
      * ライン数
      * 種類
      * プルリクエスト送信者の名前
    * ベースラインの指標
    * 継続的なトラッキング
      * 人的・物的リソース
        * 費用
      * 時間
    * 測定結果を誰が閲覧するか？コミュニティへ開示するか？
  * バグ修正
* 製品責任者
