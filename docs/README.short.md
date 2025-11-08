# 職務経歴書

分量の関係で一部省略、完全版は下記に記載。
<br/>
https://github.com/KazukiHayase

# 基本情報

|項目|詳細|
|---|---|
|氏名|早瀬和輝|
|生年月日|1999/01/02|
|居住地|東京都|
|GitHub|https://github.com/KazukiHayase|
|X|https://x.com/KazukiHayase|
|Zenn|https://zenn.dev/kazu777|
|Speaker Deck|https://speakerdeck.com/Kazukihayase|

# 職務要約

約5年間にわたり、フルスタックエンジニアとして、Google Cloud、Go、GraphQL、React を中心に、インフラ・バックエンド・フロントエンドの開発に従事。

株式会社BuySell Technologiesでは、リユース特化のOMS開発にプロジェクトマネージャー兼テックリードとして参画。
技術選定や開発プロセスの整備を推進し、開発効率向上に貢献。PdMと協力し、ユーザー視点を重視した開発を実践。

現在は株式会社ドクターズプライムにて、医師向け求人マッチングプラットフォームの開発・運用に従事。
リードエンジニアとして、新規機能開発や技術的負債の解消、DevOps改善を推進。社内オペレーション自動化のための機能群の設計・実装や、CI高速化などの取り組みを通じて、事業とプロダクトの成長に貢献。

今後は、事業目標達成にコミットしながら、技術力をさらに深めていきたいと考えている。

# 技術スタック

|項目|詳細|
|---|---|
|インフラ|Google Cloud、AWS、Terraform、SAM|
|データベース|PostgreSQL、DynamoDB|
|バックエンド|GraphQL、Hasura、OpenAPI、OpenAPI Generator、oapi-codegen、Go、Ruby on Rails、Elasticsearch|
|フロントエンド|React、Next.js、TypeScript、Apollo Client、GraphQL Code Generator、React Hook Form、zod、MUI、Storybook|
|CI・CD|GitHub Actions、CircleCI|
|ツール|Jira、Confluence、Slack、Sentry|

# 自己PR

## ユーザー志向

「なぜやるか」を常に考え、ユーザーに価値を提供することを重視して開発を行っている。
技術が好きでエンジニアリングに携わり続けたいという思いはあるが、それ以上にユーザーの課題を解決したいという気持ちが強い。
実際に、開発業務を一時的に離れ、ユーザーインタビューや要件定義などのPdM業務に専念した期間もある。

## リード力

チームの課題を発見し、解決するリード力を持っている。
リーダーやプロジェクトマネージャーとして、チーム全体を俯瞰し、課題を見つけ解決することに取り組んできた。
チームが抱えている優先度の高い課題に対しては、メンバーを巻き込みながら、チーム全体で解決策を考え、実行することを主導してきた。

## アウトプット力

仕様理解力の高さ、キャッチアップ力、概念整理の速さを強みとし、個人としてのアウトプット量も多い。
直近ではAIも積極的に活用しながら、開発生産性の向上に努めている。

# 今後やりたいこと

## 事業目標にコミットする

エンジニアリングはあくまで手段であり、最終的には事業に貢献することが目的であると考えている。
事業貢献が求められる環境で、目標を達成するために手段や過程をチームで考え、試行錯誤しながら事業目標達成に向けてコミットしたい。

## 技術を深める

今後は技術力を伸ばし、引き出しの多さを増やしていきたい。
現時点では、技術の幅や深さが十分ではないと感じているため、高い水準が求められる環境で経験を積むことで、技術力を高めていきたい。

# 職務経歴

## 2025/04 ~ 現在 株式会社 ドクターズプライム

### 医師向け求人マッチングプラットフォームの開発・運用

#### 概要

|項目|詳細|
|---|---|
|期間|2025/04~|
|チーム構成|EM 1名、PdM 2名、エンジニア 3名|
|役割|リードエンジニア、フルスタックエンジニア|
|使用技術|**インフラ**<br/>Google Cloud、Terraform、PostgreSQL<br/><br/>**バックエンド**<br/>GraphQL、Hasura、Go、Ent、Twirp、Algolia<br/><br/>**フロントエンド**<br/>React、Next.js、TypeScript、Apollo Client、GraphQL Code Generator、React Hook Form、zod、Chakra UI、MUI|

#### プロジェクト内容

医師と病院のマッチングを支援するWebアプリケーションの開発に従事。
リードエンジニアとして、新機能開発やDevOps改善、メンバーの育成などを担当。

#### 主要実績

##### 社内オペレーション自動化のための機能群の設計・実装

医師向けの求人マッチングプラットフォームにおいて、社内オペレーションで対応している業務を効率化するための複数の機能の設計・実装を行った。
PdMと協業し、オペレーションの再設計や業務フローの見直しを行いながら、社内での対応が不要になるような機能開発を行った。

- RRuleを用いた繰り返しパターンの実装
- entのPrivacy機能とgo/astを用いた、DBアクセス制御の実装

##### 技術的負債の解消

プロダクトの成長に伴い蓄積された技術的負債に対し、段階的な解消を実施した。
開発の過程で使用技術の変更が行われ、移行途中で放置されていた箇所が複数存在していた。
そのため、新規機能開発と並行して、技術的負債の解消を進め、コードベースの一貫性と保守性を向上させた。

- AppEngine -> Cloud Runへの移行
- 病院向け管理画面のフルリプレイス
- Datastore -> PostgreSQLの移行に伴うダブルライト削除
- RPC -> GraphQLへの移行
- DBのデータの正規化、FK設定の追加

##### DevOps改善

チーム全体の開発効率を向上させるための施策を推進した。
CI高速化やAIツールの活用促進に加え、PdM領域へのAI活用やデザインシステムの整備など、多方面での改善を実施。

- CI高速化
- セキュリティ対策(サプライチェーン攻撃への対応)
- PdM領域へのAI活用推進
- Claude Codeの活用推進とベストプラクティスの共有
- デザインシステムの整備

[CIでのgolangci-lintの実行を約90%削減した話](https://speakerdeck.com/kazukihayase/cidenogolangci-lintnoshi-xing-woyue-90-percent-xue-jian-sitahua)<br/>
[go testのキャッシュの仕組みを理解して、テストコードを変えずにCIを高速化する](https://zenn.dev/drsprime/articles/go-test-cache-ci-optimization)<br/>
[Claude Codeを開発の全フェーズで活用したら開発生産性が1.5倍に向上した](https://zenn.dev/drsprime/articles/3eeb7d95e954ea)<br/>
[要件定義・デザインフェーズでもAIを活用して、コミュニケーションの密度を高める](https://speakerdeck.com/kazukihayase/yao-jian-ding-yi-dezainhuezudemoaiwohuo-yong-site-komiyunikesiyonnomi-du-wogao-meru)

## 2021/04 ~ 2025/03 株式会社 BuySell Technologies

### リユース特化のOMS（Order Management System）の開発

#### 概要

|項目|詳細|
|---|---|
|期間|2021/07~2025/03|
|チーム構成|EM 1名、PdM 1名、バックエンド 8名、フロントエンド 2名|
|役割|プロジェクトマネージャー、テックリード|
|使用技術|**インフラ**<br/>Google Cloud、Terraform、PostgreSQL<br/><br/>**バックエンド**<br/>GraphQL、Hasura、OpenAPI、oapi-codegen、Go、gqlgen、GORM、Elasticsearch<br/><br/>**フロントエンド**<br/>React、Next.js、TypeScript、Apollo Client、GraphQL Code Generator、React Hook Form、zod、MUI、Storybook|

#### プロジェクト内容

複数のECサイトへの出品・受注業務を一元管理するWebアプリケーションの開発。
複数のECサイトへの出品や受注管理を他社SaaSで行っていたが、パフォーマンスが低さや不具合の多さから、事業のスケールを阻害していたため、内製で開発を行うことになった。
自社だけの利用ではなく、将来的にSaaSとして外部に提供していくことも考慮して設計・実装を行った。

#### 主要実績

##### プロダクト全体の技術選定

バックエンド・フロントエンド両方の技術選定に携わった。

[3年間に及ぶ新規プロダクト開発の技術選定の振り返り](https://tech.buysell-technologies.com/entry/adventcalendar2024-12-01)<br/>
[もし今からGraphQLを採用するなら](https://speakerdeck.com/kazukihayase/mosijin-karagraphqlwocai-yong-surunara)

##### 開発生産性向上のための取り組み

チームリーダーとして、スクラムの導入や開発生産性向上のための取り組みを主導した。
具体的には、KPIとしてPR作成数を設定し、KPIを達成するための施策をスプリントごとに検討・実施を行った。

[生産性が上がり続けるチームを作るための第一歩](https://speakerdeck.com/kazukihayase/sheng-chan-xing-gashang-garisok-kerutimuwozuo-rutamenodi-bu)<br/>
[自分だけが頑張るのをやめて、フルスタックなチームを作る](https://speakerdeck.com/kazukihayase/zi-fen-dakegawan-zhang-runowoyamete-hurusutatukunatimuwozuo-ru)

##### 可変項目のDB設計

ユーザーが自由に商品に対して項目や選択肢を定義でき、それを使った複雑かつ高速な検索が求められていた。
この要件を満たすため、商品の可変属性データはPostgreSQLでEAV（Entity-Attribute-Value）を用いて管理し、そのデータをElasticsearchに同期して検索を行う方式を採用した。

##### バックエンドの自動テストの整備

開発が進むにつれて、モックやテストデータのセットアップが複雑であることや、記法が統一されていないことなど、バックエンドの自動テストに関連する複数の課題が顕著になり、それにより開発効率が低下していた。
そこで、バックエンドの自動テストの整備を行い、開発効率の向上を図った。

[Goでテストをしやすくするためにやったこと](https://speakerdeck.com/kazukihayase/gotetesutowosiyasukusurutameniyatutakoto)<br/>
[GoのTestifyを使って独立したサブテストを実現する](https://tech.buysell-technologies.com/entry/2023/11/30/091518)<br/>
[Goのジェネリクスを使って、テーブル駆動テスト(TDT)に統一性を持たせる](https://zenn.dev/buyselltech/articles/ef92713b8dde8a)

##### フロントエンド構成の整備

開発効率の向上や属人化の防止を目的として、フロントエンドの構成を整備した。
ルールを設けたり明文化することは重要だが、ルールの認知漏れや認識齟齬がどうしても発生してしまう。
そのため、自動生成ツールを整備やCIへの組み込みなど、可能な限り仕組み化・自動化を意識して整備を行った。

[開発効率を上げるためのモダンなフロントエンド構成](https://tech.buysell-technologies.com/entry/adventcalendar2023-12-01)<br/>
[MUIをベースにしたデザインシステムの構築](https://tech.buysell-technologies.com/entry/2023/01/31/000000)<br/>
[graphql-eslintを使用してGraphQLの命名規則を強制するカスタムルールを作る](https://zenn.dev/buyselltech/articles/fc1479f4fed63d)

### EC出品用商品撮影アプリのフルリプレイス

#### 概要

|項目|詳細|
|---|---|
|期間|2021/04~2024/08|
|チーム構成|PdM 1名、iOS 3名、バックエンド 2名 |
|役割|フルスタックエンジニア|
|使用技術|**インフラ**<br/>AWS、AWS SAM、Lambda、DynamoDB<br/><br/>**バックエンド**<br/>OpenAPI、OpenAPI Generator、Go<br/><br/>**iOS**<br/>Swift、RxSwift|

#### プロジェクト内容

リユース事業の出品業務における商品撮影アプリのフルリプレイスプロジェクト。

撮影が完了したものから順次出品していくという業務フローであったため、撮影効率が出品効率並びに売り上げに影響していた。そのため撮影効率向上のために業務フロー自体の見直しを行うことになったが、既存アプリが特定の業務フローのみにしか対応していない仕様であったので既存アプリのままでは業務フローの変更が行えない状況であった。
また既存アプリではパフォーマンス・保守性がともに低く、将来的なことも考えた結果、リプレイスするに至った。

3ヶ月で開発~テストまで行い、リリースに至った。
既存アプリからのリプレイスを完遂し、業務時間を20%削減することに成功した。

#### 主要実績

##### AWS Step Functionsを用いたバッチ処理の実装

AWS Step Functionsを用いて画像の生データを別のS3にコピーし、出品管理サービスのFTPサーバーへアップロードするバッチ処理を実装した。
Lambda単体の責務は小さくし、実行順序はStep Functionsで管理することで、Lambda同士を疎結合にし保守性が高くなるように設計した。

この構成にしたことで、リリース後に連携先を増やすことがあったが、その際も既存のLambdaに手を加えることなく、新規Lambdaの実装とStep Functionsの設定のみで対応できた。
