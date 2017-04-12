---
title: 教育への取組み
layout: foundation.hbs
newsletter:
  title: Subscribe to get updates and give input for education initiatives
  id: f5f8d4eddb
---

<!--
## Education in Node.js

Here we will ask fun questions like, 'what is education in [Node.js](https://nodejs.org/en/)?'

Notice we didn't say 'answer'? Education initiatives from the Node.js Foundation explore what it means to be learning Node.js. Who uses it? How are folks learning it? How can we as a community make the experience better and inclusive for existing users and rad, diverse group of learners?
-->

## Node.jsでの教育

ひとつ楽しい質問をしてみましょう。[Node.js](https://nodejs.org/ja/)の教育とは何でしょう？

ここではその答えは言いません。
Node.jsを学ぶことの意味を探究することが、Node.js財団の教育への取り組みなのです。
Node.jsを使うのは誰でしょう？その人達はどのように学ぶのでしょう？
既存または急進的なユーザーを含め「学ぶ人々の多様性」を包括しながらも、より良い学習体験の手助けの為に、私たちはコミュニティーとして何が出来るでしょう？


<!--
A few people who are exploring this currently:

- [Tracy Hinds](https://twitter.com/HackyGoLucky), Education Community Manager for the Node.js Foundation
- Education Advisory Group for the Node.js Foundation
- Lots of awesome community folks who have been doing cool stuff for a while in Node.js and deserve to be heard, like you!

Please participate. [File issues, PRs, and create the community you'd like to be a part of](https://github.com/nodejs/education).
-->

探究中の人々:

- [Tracy Hinds](https://twitter.com/HackyGoLucky), Node.js財団の教育コミュニティーマネージャー
- Node.js財団の教育諮問グループ
- 長くクールな活動をしてきた注目に値する沢山のすばらしいコミュニティの人たち (あなたの様に！)


 [イシューやプルリクエスト、あなたが参加したいと思うコミュニティ作りの相談などはこちらに](https://github.com/nodejs/education)、ぜひご参加ください。

<!--
### Roadmap

This roadmap is a living document, and it is likely that priorities will change, but the items below should give some indication of education initiatives for this calendar year.
-->

### ロードマップ

このロードマップは常にメンテされており、優先順位は変わる可能性が高いですが、以下の項目は今年の教育方針を示すものです。

<!--
**Certification**

The Node.js Foundation (in partnership with The Linux Foundation) will be performing the following tasks to build and ship the Node.js certification:
-->

**認証制度**

Node.js財団は（Linux財団と提携して）、Node.js認証制度の開始に向け次のように準備を進めています。



<!--
- Define Certification(s), the number of levels (parallel or sequential), titles, program goals
-->
- 認証の種類、難易度や数（並列か階層か）、肩書き、プログラムの目標を定義する

<!--
- Define Scope Statement of Certification
-->
- 認証制度のスコープ・ステートメントを定義する

<!--
- Define the in-browser hosted exam environment which will be provided to candidates. Must be exactly reproducible and consistent in function.
-->
- 候補者に提供されるブラウザ内試験環境を定義します。正確な再現性と、機能の一貫性が必須です。

<!--
- Conduct job task analysis(JTA) which is to define the Domains of work and corresponding Tasks within each domain a Certification Candidate should be able to perform
-->
- 認定候補者が実行できるはずの各ドメイン内の作業ドメインと対応するタスクを定義するための
職務分析(JTA)を実施する

<!--
- Define the exam blueprint containing the specific exam Domains and Tasks and their relevant weight within the exam(Domains and Tasks will be opensourced. Blueprint will be secure and not public facing, testrunner will also be opensourced).
-->
- 特定の試験のドメインとタスク、および関連する重さが試験内に含まれている試験の青写真を定義します（ドメインとタスクはオープンソースになります。青写真は安全で公然たるものではなく、テストランナーもオープンソースになります）。

<!--
- Publish determined domains and tasks for ecosystem to prepare complementary trainings with ample notice.
-->
- 十分な注意を払って補完的なトレーニングを準備するために、エコシステムのために決定されたドメインとタスクを公開する。

<!--
- Write performance-based exam items (problems to solve) based on the Domains and Tasks defined by the JTA
-->
- JTAによって定義されたドメインとタスクに基づいて、パフォーマンスベースの試験項目を書く（問題を解決する）
<!--
    - Exam items must be written and formatted to comply with an auto-grade script that is run on answers provided (i.e. machine-gradeable)
-->
     - 試験項目は、提供された回答（つまり、マシングレード可能）で実行される自動グレードのスクリプトに準拠するように書かれ、フォーマットされていなければなりません
<!--
    - Consideration of non-English speaking users including items written in a way that they are translatable
-->
     - 翻訳可能な方法で書かれた項目を含む英語以外のユーザーの検討

<!--
- Provide subject matter expert (SME) support and review to
    - Script and program the exam items
    - Set-up Certification registration portal
    - Deploy the exam
-->
- 主題専門家（SME）のサポートとレビューを提供する
     - 試験項目のスクリプトとプログラム
     - 認証登録ポータルの設定
     - 試験を展開する


<!--
- Conduct secure pilot testing (alpha, beta)
-->
- 安全なパイロットテストを実施する（アルファ、ベータ）

<!--
- Determine the exam passing score via psychometrician-led standard setting process
-->
- 精神測度主導の標準設定プロセスを通した試験合格点の決定

<!--
- Support the public launch of the exam including program marketing
-->
- プログラムマーケティングを含む試験の一般公開をサポートする

<!--
- Manage certification program including:
- 以下を含む認証プログラムを管理する：
<!--
    - Creation and documentation of program policies and procedures (Candidate Handbook, Candidate Agreement, etc.)
-->
     - プログラムの方針と手順の作成と文書化（候補者ハンドブック、候補者合意書など）
<!--
    - Technical support and help desk
-->
     - テクニカルサポートとヘルプデスク
<!--
    - Candidate appeals and sanctions considerations
-->
     - 候補者の控訴および制裁に関する検討事項
<!--
    - Regular SME advisory from cert advisory board and consultants
-->
     - 諮問委員会およびコンサルタントからの定期的なSME勧告
<!--
    - Regular renewal of job analysis and item creation (example: every 3 years)
-->
     - ジョブ分析とアイテム作成の定期的な更新（例：3年ごと）

<!--
Work may be organized into committees or subcommittees representing, but not limited to the following:
-->

仕事は、以下を代表する委員会または小委員会に編成することができます。

<!--
- Job Analysis Committee--define the Domains of work and corresponding Tasks within each domain a Certification Candidate should be able to perform
-->
- 職務分析委員会 - 認定候補者が実行できるはずの各ドメイン内の作業ドメインと対応するタスクを定義する
<!--
- Item Writing Committee--writing/developing the individual item tasks into problems for the exam.
-->
- 項目執筆委員会 - 個々の項目の課題を試験の問題に執筆/開発する。
<!--
- Standard Setting Committee--will set the passing/cut score. This process is led by the psychometrician. Aggregation of scores weighted by the committee.
-->
- 標準設定委員会 - 通過/カットスコアを設定します。 このプロセスは、精神測定家によって導かれる。 委員会によって重み付けされたスコアの集計。
<!--
- Certification Advisory Board--perspectives from industry experts for the cert lead(education community manager) for essential decisions related to standards, policies, and procedures of the certification.
-->
- 認証諮問委員会 - 証明書の基準、方針、および手順に関連する重要な決定について、証明書主任（教育コミュニティ管理者）の業界専門家からの見通し。

<!--
Work will be divided into collaborative group sessions and individual self-paced assignments in accordance with project schedule. Time commitments will vary.
-->

仕事は、プロジェクトのスケジュールに従って、コラボレーション・グループ・セッションと個々の自己ペース割り当てに分かれます。 時間の約束は変わるでしょう。

<!--
**Docs**
- Stay tuned and help your friends at the [Docs WG](https://github.com/nodejs/docs)
-->

**ドキュメント**
- [Docs WG]（https://github.com/nodejs/docs）で調整してお友達を助けてください。

<!--
**Resources for learning Node.js**
- Stay tuned and participate [in our convos](https://github.com/nodejs/education/issues/4)
-->
** Node.jsを学ぶためのリソース**
- チューニングし、[私たちのconvos]に参加する（https://github.com/nodejs/education/issues/4）

<!--
## Contact

For questions about education initiatives or a little inspiration, please send an
email to [tracyhinds@linuxfoundation.org](mailto:tracyhinds@linuxfoundation.org?subject=Education-questions).
-->
##お問い合わせ

教育イニシアチブやインスピレーションについての質問は、
[tracyhinds@linuxfoundation.org]（mailto：tracyhinds@linuxfoundation.org？subject =教育質問）に電子メールを送ってください。

