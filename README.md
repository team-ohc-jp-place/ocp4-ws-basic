# ハンズオン概要
本ハンズオンは，OpenShift4の基礎編です。  
インフラ向け応用編(Operator他)および開発向け応用編(CodeReady他)のワークショップも不定期開催しています。

OpenShift4基礎編では以下を学びます。
- OpenShift4クラスターへのログインと動作確認
- コンテナイメージのビルドとデプロイ
- Jenkinsベースのビルドパイプラインの使用

### Lab1: [OpenShift4クラスター構築，ログインと動作確認，コンテナイメージのビルド&デプロイ](Lab1)
### Lab2: [Jenkinsベースのビルドパイプラインの使用，その他](Lab2)

# ハンズオン環境
本ハンズオンは，構築済みのOpenShift(OCP)クラスターを参加者全員で共有して作業を進めます。

OCPクラスターに対するCLI操作を行う際は，CodeReady Workspaceにユーザー登録して頂き、作成した開発環境から行います。GUI操作は，クライアントPCのブラウザ(**Chrome/Firefox推奨**)を使用します。

[Setup Workspace](setup_workspace) をご確認の上、ご自身の開発環境をセットアップしてください。本日のCodeReady WorkspaceのURLは下記になります。

http://codeready-codeready.apps.ws.ocp41.nosue.mobi 

# 前提
- ブラウザ (Google Chrome or Firefox)

# 注意事項
OpenShift4クラスター接続情報など当日の連絡事項 (Etherpad) ==> 当日ご案内します

# タイムテーブル
Red Hat OpenShift Container Platform 4 ワークショップ

|Time|Agenda|Content|
|:---:|:---|:---|
|13:00-13:30|受付||
|(30min)|<講義> OpenShift4概要 と ハンズオン環境への接続|OpenShift4の特徴紹介||
|(60min)|<ハンズオン> Lab1 <br>|OpenShift4インストール手順確認<br>ログインと動作確認<br>コンテナイメージのビルド&デプロイ|
|(15min)|Break||
|(30min)|<講義> OpenShift4でのアプリケーションデプロイ概要|S2I (Source to Image) <br> CI/CD|
|(45min)|<ハンズオン> Lab2 <br>|Jenkinsベースのビルドパイプライン<br>その他コンテンツ|
|(-17:00)|アンケート記入，QA，フリーディスカッションタイム||
