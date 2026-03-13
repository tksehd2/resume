# 経歴書

<div class="profile-header">
  <img src="assets/photo.jpg" alt="Profile Photo">
  <div class="profile-info">
    <h1><ruby>辛<rp>(</rp><rt>シン</rt><rp>)</rp></ruby>　<ruby>東赫<rp>(</rp><rt>ドンヒョク</rt><rp>)</rp></ruby></h1>
    <div class="profile-meta">
      <span><span class="label">最寄駅</span> 有楽町線 豊洲駅</span>
      <span><span class="label">年齢</span> 40歳</span>
      <span><span class="label">性別</span> 男性</span>
      <span><span class="label">配偶者</span> 有</span>
      <span><span class="label">学歴</span> 湖西大学校 パソコン工学 卒業</span>
    </div>
  </div>
</div>

---

## 得意分野・スキル

<div class="skills-section">

<div class="skill-category">
<h3>強み</h3>

- **Unity / C# によるシステム基盤設計 10年以上** — シーン管理、通信API、UI基盤など、ゲームの根幹を設計・実装
- **CI/CD・テスト自動化基盤の構築** — Jenkins・GitHub Actionsを活用し、テストカバレッジ90%以上の品質基盤を実現
- **AIを活用した開発生産性の向上** — コードレビュー自動化からツール制作まで、AIを実務に積極導入

</div>

<div class="skill-category">
<h3>得意技術</h3>
<div class="skill-tags">
  <span class="tag primary">Unity</span>
  <span class="tag primary">C#</span>
  <span class="tag">Java</span>
  <span class="tag">Jenkins / CI/CD</span>
  <span class="tag">Git / GitHub Actions</span>
  <span class="tag secondary">Python</span>
  <span class="tag secondary">Docker</span>
  <span class="tag secondary">ASP.NET</span>
  <span class="tag secondary">MySQL / MS-SQL</span>
</div>
</div>

</div>

---

## 経歴サマリー

<div class="career-summary">

| 期間 | 会社 | 概要 |
|------|------|------|
| 2020.10 ～ 現在 | 株式会社Cygames | マルチプラットフォームゲームのシステム設計・品質基盤構築（サブリーダー） |
| 2018.12 ～ 2020.08 | ビットキャッシュ株式会社 | Webサービスのバックエンド開発、CI/CD整備、開発環境改善 |
| 2017.06 ～ 2018.11 | 株式会社gumi | 2v2通信対戦ゲームのバトルシステム・AI・通信同期開発 |
| 2016.09 ～ 2017.05 | 株式会社gumi | 2v2対戦ゲームのAIツール・アビリティ・UI開発 |
| 2014.01 ～ 2015.12 | Cocosoft | ボクシングゲームの新規開発（UI・サーバー・インフラ・ビルド自動化） |
| 2012.09 ～ 2013.12 | Cocosoft | ボクシングゲームの運営・パッチ開発（総括ディレクタ） |
| 2011.02 ～ 2012.09 | Doouky（創業） | スマホアプリ・ゲーム複数タイトル開発（CTO） |

</div>

---

## 職務経歴

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2020年10月 ～ 現在</span>

### マルチプラットフォームゲーム開発 ― 株式会社Cygames

<div class="career-meta">
  <span>🛠 <span class="badge">Unity / C#</span></span>
  <span>👥 規模：社外秘</span>
</div>

#### 役割

- エンジニアサブリーダー
- アウトゲームパートリーダー
- システムパートリーダー

#### 設計・実装

- ゲームシーントランジションシステムの設計・実装
- ゲームシーンのパラメータライズの設計・実装
- リソース管理システムの設計・実装
- ゲーム内共通UIコントローラーの設計・実装（ボタン、画像、スクロール等の共通コンポーネント）
- 通信API基盤システム（通信、データ更新、エラーハンドリング等）の設計・実装
- ゲーム全般のエラーハンドリング設計・実装
- ゲームパッド対応の設計・実装

#### 品質向上

- Unity Test Frameworkを導入し、通信APIのテストケースを作成（Coverage 90%以上、100%目標）
- UIやゲームロジックのUnit Testを実装
- ゲームシーンの結合テストを実装し、PR時にGitHub Actionsで自動テストを実行
- 自動テストシナリオシステムの設計・実装
- 自動テストのログ記録用Webサービスプラグインの実装、ログデータ設計
- 定期的なリファクタリングと的確なコードレビュー
- PR時にAIが差分をレビューするプロンプトの作成・検証・メンテナンス（Git連携）
- コード品質向上のためのIDE設定管理、コード警告の通知システムを設計・実装
- マスタデータ検証システムの設計・実装

#### AI活用

*ChatGPT / Gemini / Claude Code / Antigravity*

- CI/CD上でAIがコードベース全体を順次読み込み・レビューし、問題箇所の修正から修正根拠を添えたPR作成までを自動で行うレビューシステムの設計
- プレハブのAIレビューシステムの設計・導入
- AIを活用した開発支援ツールの制作により作業生産性を大幅に向上
  - フォントプリセット編集ツール
  - リソース依存関係の確認ツール
  - ゲーム内デバッグメニューツール 等

#### 育成・教育

- デザイナー向けにUnity AutoLayout講座を実施、チュートリアル作成、サンドボックス環境を構築
- エンジニア向けにTDDを用いたクラス設計手法を共有

#### その他

- Jenkins・GitHub Actionsのメンテナンスおよび機能追加
- GitHub Pages・Docfxを用いたマスタデータ検証テストケースの文書化（プランナー向け、毎日自動更新）

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
  <span class="phase">結合テスト</span>
  <span class="phase">総合テスト</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2018年12月 ～ 2020年8月（20ヶ月間）</span>

### ウェブサービス開発（バックエンド） ― ビットキャッシュ株式会社

<div class="career-meta">
  <span>🛠 <span class="badge">Java / JSF 2.2 / Python / Kotlin</span></span>
  <span>💾 <span class="badge">MySQL</span></span>
  <span>🖥 <span class="badge">CentOS</span></span>
  <span>🔧 <span class="badge">Git / SVN / Eclipse / IntelliJ / Payara5</span></span>
  <span>👥 5人</span>
</div>

#### 賞金支払サービスの開発・運用管理

*JSF 2.2、PrimeFaces、Payara5*

- 長期間遅延していたプロジェクトを短期間でリリースし、円滑な運用体制を構築
- 既存コードを分析し、リファレンスドキュメントと設計図を作成
- 運用会社向け管理画面の開発
- ユーザー向け賞金申請画面の開発
- 管理画面のマニュアルおよび運用ガイドラインを作成

#### 社内向け月次集計ツールの開発

*Java、Python、Jenkins*

- 手作業で行っていた月次集計をワンクリックで実行できるようシステム化
- 社内フレームワークを利用しJavaで開発
- フレームワークの制約（大量データによるリクエストタイムアウト等）によりPythonで再構築
- 非エンジニアでも利用できるよう、Jenkinsを活用しUIを工夫
- Jenkins Pipelineで一括ビルド設定を実現
- ビルドトリガーによるスケジュール自動ビルドを実現

#### 社内全サービスの自動ビルド化

- 手作業で行っていたビルド・デプロイをワンクリックで完結するようシステム化
- Jenkins Pipelineで一括ビルド設定を実現

#### Java → Kotlin 移行検証

- コードの保守性向上を目的にJavaからKotlinへの移行を推進
- パフォーマンスへの影響はなく、コードの可読性が向上

#### SQLクエリチューニング

- 負荷の高いクエリのチューニングを実施
- インデックス追加だけでなくクエリ構造自体を見直し、条件付き会員検索の応答速度を大幅に改善
- 3時間以上かかっていたクエリをすべて1分以内に短縮

#### 開発環境改善

- 共用サーバー1台に依存していた開発環境を、Dockerによるローカル環境に移行
- DockerfileとImageを最適化し、ワンクリックで環境構築・起動できるよう整備
- 手動デプロイをワンクリックでビルドからデプロイまで完結するよう自動化

#### 習得スキル

- 遅延プロジェクトの立て直し・管理ノウハウ
- BtoB向けマニュアル作成のノウハウ
- テストケースの作成・運用ノウハウ
- Dockerの構築・運用ノウハウ

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
  <span class="phase">結合テスト</span>
  <span class="phase">総合テスト</span>
  <span class="phase">保守・運用</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2017年6月 ～ 2018年11月（18ヶ月間）</span>

### スマホゲーム制作：2対2通信対戦ゲーム（Android, iOS） ― 株式会社gumi

<div class="career-meta">
  <span>🛠 <span class="badge">Unity3D / Java / C#</span></span>
  <span>🔧 <span class="badge">Git / VS2015 / Eclipse</span></span>
  <span>👥 9人</span>
</div>

#### 担当業務

- バトル編集ツールの開発・保守（Unity拡張）
- バトルHUDおよびUI全般の開発（NGUI）
- 自社タイムラインツールの機能追加・保守（Unity拡張）
- タイムラインツール用デバッグツールの開発（Unity拡張）
- ドローンAIの設計・実装
  - 移動制御AI
  - 群衆AI
  - 射撃・アビリティ制御AI
  - サウンド・エフェクト制御AI
- 各種アビリティの実装
  - 近距離・遠隔アビリティ
  - 歩き撃ちアビリティ
  - 溜め撃ちアビリティ
- Unity標準タイムスケールに代わる独自タイムスケールシステムの開発・保守（オブジェクト単位で個別調整可能）
- 実機向けデバッグ機能の開発・保守
- パフォーマンス最適化（GC最適化、CPU使用率最適化）
- バトルコードの全面リファクタリング・保守
- バトルオートモードの実装
- BoxCastの問題を分析し、OverlapBox＋ClosestPointによるヒット判定に改善
- バトル全般の通信同期処理を担当
- 通信遅延対策の研究・実装
- 弾道・アビリティ（ドローン等）の移動軌道の研究・実装

#### 習得スキル

- コードレビューを軸とした開発プロセスのノウハウ
- リアルタイム通信対戦の同期技術
- 開発支援ツールの設計・制作ノウハウ
- Gitの運用ノウハウ
- Unityタイムスケールのカスタマイズ手法
- 3Dコリジョンの実践的なノウハウ

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
  <span class="phase">結合テスト</span>
  <span class="phase">総合テスト</span>
  <span class="phase">保守・運用</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2016年9月 ～ 2017年5月（9ヶ月間）</span>

### スマホゲーム制作：2対2通信対戦ゲーム（Android, iOS） ― 株式会社gumi

<div class="career-meta">
  <span>🛠 <span class="badge">Unity3D / Java / C#</span></span>
  <span>🔧 <span class="badge">Git / VS2015 / Eclipse</span></span>
  <span>👥 7人</span>
</div>

#### 担当業務

- 自社AIシステム用の編集ツール開発・保守（Unity拡張）
- AIデバッグツールの開発・保守（Unity拡張）
- FBXインポートツールの開発（Unity拡張）
- プレイヤーキャラクター用アビリティの実装
- プレイヤーが操作するドローンの実装（アビリティ系）
- バトルHUDおよびUI全般の開発（NGUI）
- 各種アビリティの実装
  - 近接・遠隔アビリティ
  - 状況別パッシブアビリティ
  - 状況別アクティブアビリティ
- 弾道・アビリティの移動軌道の研究・実装
- Jenkinsによるデイリービルドシステムの構築
- 実機向けデバッグ機能の開発・保守

#### 習得スキル

- 受託開発におけるコミュニケーションのノウハウ
- コードレビューを軸とした開発プロセスのノウハウ
- 開発支援ツールの設計・制作ノウハウ
- Gitの運用ノウハウ

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2014年1月 ～ 2015年12月（24ヶ月間）</span>

### スマホゲーム開発：非同期通信対戦ボクシングゲーム（Android, iOS） ― Cocosoft

<div class="career-meta">
  <span>🛠 <span class="badge">Unity3D 4.x / C# / ASP.NET</span></span>
  <span>💾 <span class="badge">MS-SQL / Couchbase</span></span>
  <span>🖥 <span class="badge">Windows Server 2008</span></span>
  <span>🔧 <span class="badge">Subversion / Redmine / VS2013 / Jenkins / HockeyApp</span></span>
  <span>👥 13人</span>
</div>

新規ゲームの企画段階から参画し、設計・開発・運営を担当

#### 担当業務

- クライアント側UIシステムの開発
- ゲームサーバーインフラの設計
- サーバーシステムおよびコンテンツの設計・開発
- Jenkinsによるビルド自動化・デイリービルドシステムの構築（Android / iOS）
- ミドルウェア開発（データ検証、ビルドツール、リソース自動アップロード等）
- FGT（Focus Group Test）の計画立案・実施

#### 習得スキル

- Jenkinsによるビルド自動化のノウハウ
- インタラクティブUI設計のノウハウ
- Unity最適化およびゲーム設計のノウハウ
- DAU 20万以上のサービス運営経験

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
  <span class="phase">結合テスト</span>
  <span class="phase">総合テスト</span>
  <span class="phase">保守・運用</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2012年9月 ～ 2013年12月（16ヶ月間）</span>

### スマホゲーム開発：シングルプレイボクシングゲーム（Android, iOS） ― Cocosoft

<div class="career-meta">
  <span>🛠 <span class="badge">Unity3D 3.x / C# / ASP.NET</span></span>
  <span>💾 <span class="badge">MS-SQL</span></span>
  <span>🖥 <span class="badge">Windows Server 2008</span></span>
  <span>🔧 <span class="badge">Subversion / Redmine / VS2013 / HockeyApp</span></span>
  <span>👥 2人 ― 総括ディレクタ</span>
</div>

ゲームの保守・追加開発を担当

#### 担当業務

- ユーザーニーズの分析に基づくパッチ計画の立案
- パッチの企画、クライアント・サーバー開発
- Android / iOS決済モジュールの改善
- LINE版パンチヒーローの開発・運営

#### 習得スキル

- ユーザーニーズ分析のノウハウ
- MS-SQLの最適化・設計
- ソーシャル連携（LINE友達等）の活用ノウハウ
- 企業間の業務連携ノウハウ

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">総合テスト</span>
  <span class="phase">保守・運用</span>
</div>

</div>

<!-- =============================== -->
<div class="career-entry">

<span class="career-period">2011年2月 ～ 2012年9月（20ヶ月間）</span>

### スマホゲーム開発（Android, iOS） ― Doouky（創業）

<div class="career-meta">
  <span>🛠 <span class="badge">Android / Unity3D / C# / Java / JavaScript / Bootstrap</span></span>
  <span>💾 <span class="badge">Google App Engine Memcached</span></span>
  <span>🖥 <span class="badge">Google App Engine / Amazon BeansTalk</span></span>
  <span>🔧 <span class="badge">Subversion / Redmine</span></span>
  <span>👥 9人 ― CTO</span>
</div>

会社を創業し、複数タイトルの企画・開発・運営を推進

#### 開発タイトル

- 湖西大学校の図書館空席確認アプリ
- Timetable設定アプリ
- 湖西大学校のシャトルバス時刻表アプリ
- リーグ・オブ・レジェンド スキンビューアアプリ
- ディアブロ アイテムギャラリーアプリ
- アチャリースター（弓ゲーム）
- ホワイト・ヘブン・ブリッジ（ランナーゲーム）

#### 習得スキル

- Google App Engineの運用ノウハウ
- Amazon Elastic Beanstalkの運用ノウハウ
- AWS全般の基礎知識
- Android・Unity3D開発の実践スキル
- Android UI/UX開発スキル
- 広告モデルアプリのマネタイズ戦略

<div class="phases">
  <span class="phase">要件定義</span>
  <span class="phase">基本設計</span>
  <span class="phase">詳細設計</span>
  <span class="phase">実装・単体</span>
  <span class="phase">結合テスト</span>
  <span class="phase">総合テスト</span>
  <span class="phase">保守・運用</span>
</div>

</div>
