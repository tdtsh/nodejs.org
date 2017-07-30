---
title: 教育活動
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

それらを探究中の人々はこちら:

- [Tracy Hinds](https://twitter.com/HackyGoLucky), Node.js財団の教育コミュニティーマネージャー
- Node.js財団の教育諮問グループ
- 長くクールな活動をしてきた注目に値する沢山のすばらしいコミュニティの人たち (あなたの様に！)


 [イシューやプルリクエスト、あなたが参加したいと思うコミュニティ作りの相談などはこちらに](https://github.com/nodejs/education)、ぜひご参加ください。

<!--
### Roadmap

This roadmap is a living document, and it is likely that priorities will change, but the items below should give some indication of education initiatives for this calendar year.
-->

### ロードマップ

このロードマップは常にメンテされており優先順位は変わる可能性が高いですが、以下の項目は今年の教育方針を示すものです。

<!--
**Certification**

The Node.js Foundation (in partnership with The Linux Foundation) will be performing the following tasks to build and ship the Node.js certification:
-->

**認証制度**

Node.js財団は（Linux財団と提携して）、Node.js認証制度の開始に向け次のように準備を進めます。



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
- 候補者に提供されるブラウザ内試験環境を定義する。正確な再現性と、機能の一貫性が必須となる。

<!--
- Conduct job task analysis(JTA) which is to define the Domains of work and corresponding Tasks within each domain a Certification Candidate should be able to perform
-->
- 認定候補者が実行しうる各ドメイン内の対応するタスクと、仕事のドメインを定義するための職務分析(JTA)を実施する

<!--
- Define the exam blueprint containing the specific exam Domains and Tasks and their relevant weight within the exam(Domains and Tasks will be opensourced. Blueprint will be secure and not public facing, testrunner will also be opensourced).
-->

- 試験ドメイン、タスク、それらの重み付け（青写真は非公開かつセキュアに、ドメインとタスクはオープンソース化される。テストランナーもまた、オープンソース化される）の明確化を含む試験の青写真を定義する。


<!--
- Publish determined domains and tasks for ecosystem to prepare complementary trainings with ample notice.
-->
- 十分な注意を払って補完的なトレーニングを準備するために、決定されたドメインとタスクをエコシステムへ公開する。



<!--
- Write performance-based exam items (problems to solve) based on the Domains and Tasks defined by the JTA
    - Exam items must be written and formatted to comply with an auto-grade script that is run on answers provided (i.e. machine-gradeable)
    - Consideration of non-English speaking users including items written in a way that they are translatable
-->
- JTAによって定義されたドメインとタスクに基づき、パフォーマンスベースの試験項目（解決しべき問題）を書く
     - 試験項目は、auto-gradeスクリプトに準拠するようなフォーマットで書かれ、回答が提供された状態で実行されなければなりません。（例：machine-gradeable）
     - 非英語圏のユーザーに配慮し、試験項目は翻訳可能な方法で書かれていること

<!--
- Provide subject matter expert (SME) support and review to
    - Script and program the exam items
    - Set-up Certification registration portal
    - Deploy the exam
-->
- 主題専門家（SME）によるサポートとレビューを提供する
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
- 心理学者主導の標準設定プロセスでテストの合格ラインを決定する

<!--
- Support the public launch of the exam including program marketing
-->
- プログラムマーケティングを含む試験の一般公開をサポートする

<!--
- Manage certification program including:
    - Creation and documentation of program policies and procedures (Candidate Handbook, Candidate Agreement, etc.)
    - Technical support and help desk
    - Candidate appeals and sanctions considerations
    - Regular SME advisory from cert advisory board and consultants
    - Regular renewal of job analysis and item creation (example: every 3 years)
-->

- 以下を含む認証プログラムを管理する：
     - プログラムの方針と手順の作成と文書化（候補者ハンドブック、候補者合意書など）
     - テクニカルサポートとヘルプデスク
     - 候補者のアピールとその認可に関する検討
     - 諮問委員会およびコンサルタントからの定期的なSME勧告
     - ジョブ分析とアイテム作成の定期的な更新 (例：3年ごと)

<!--
Work may be organized into committees or subcommittees representing, but not limited to the following:
- Job Analysis Committee - define the Domains of work and corresponding Tasks within each domain a Certification Candidate should be able to perform
- Item Writing Committee-writing/developing the individual item tasks into problems for the exam.
- Standard Setting Committee-will set the passing/cut score. This process is led by the psychometrician. Aggregation of scores weighted by the committee.
- Certification Advisory Board-perspectives from industry experts for the cert lead(education community manager) for essential decisions related to standards, policies, and procedures of the certification.
Work will be divided into collaborative group sessions and individual self-paced assignments in accordance with project schedule. Time commitments will vary.
-->

作業は代表委員会や分科会に割り当てられるが、以下に限定はしない：
- 職務分析委員会--各ドメイン内において、認定候補者が実行し得る仕事のドメイン、および対応するタスクを定義する。
- 項目執筆委員会 - 個々の項目の課題を試験の問題を執筆/開発する。
- 標準設定委員会 - 合格/不合格のスコアを設定します。このプロセスは心理学者によって導かれます。 委員会によって重み付けされたスコアを集計します。
- 認証諮問委員会 - 業界専門家から認証主任（教育コミュニティマネージャ）へ、認証の手続き、ポリシー、および基準に関する重要な決定について見解。
仕事は、プロジェクトのスケジュールに従って、共同グループ・セッションと個々の自己ペース割り当てに分けられます。時間の約束は変化します。


<!--
**Docs**
- Stay tuned and help your friends at the [Docs WG](https://github.com/nodejs/docs)
-->

**ドキュメント**
- [Docs WG](https://github.com/nodejs/docs) をチェック、みんなに教えよう


<!--
**Resources for learning Node.js**
- Stay tuned and participate [in our convos](https://github.com/nodejs/education/issues/4)
-->

** Node.jsを学ぶためのリソース**
- [このやりとり](https://github.com/nodejs/education/issues/4)をチェックしてみて

<!--
## Contact

For questions about education initiatives or a little inspiration, please send an
email to [tracyhinds@linuxfoundation.org](mailto:tracyhinds@linuxfoundation.org?subject=Education-questions).
-->

##お問い合わせ

教育活動に関する質問や、ご意見は、Eメール ([tracyhinds@linuxfoundation.org](mailto:tracyhinds@linuxfoundation.org?subject=Education-questions))にて。

