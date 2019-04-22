---
copyright:
  years: 2014, 2018
lastupdated: "2018-11-14"

subcollection: virtualization
---

# Parallels Virtuozzo Containers 4.0 のクイック・リファレンス・ガイド
{: #parallels-virtuozzo-containers-4-0-quick-reference-guide}

ここには、Virtuozzo コンテナーのユーティリティーと一般的な用語について記載します。

## 汎用ユーティリティー
{: #general-utilities}

汎用ユーティリティーは、日常的な保守タスクに使用します。

|汎用ユーティリティー||
|---|---|
|vzctl|コンテナーを管理するユーティリティー。|
|vzlist|ノード上の既存のコンテナーのリストと詳細情報を表示するユーティリティー。|
|vzquota|Virtuozzo Containers のディスク割り当て量を管理するユーティリティー。|
{: caption="表 1. 汎用ユーティリティー" caption-side="top"}

## ライセンス適用ユーティリティー
{: #licensing-utilities}

ライセンス適用ユーティリティーは、新規ライセンスのインストール、ライセンスの状態の表示、新規ライセンスを求めるライセンス要求の生成に使用します。

|ライセンス適用ユーティリティー||
|---|---|
|vzlicview|Virtuozzo のライセンスの状況とパラメーターを表示するユーティリティー。|
|vzlicload|ハードウェア・ノード上の Virtuozzo ライセンスを管理するユーティリティー。|
|vzlicupdate|Virtuozzo Containers インストール済み環境のアクティブ化、ハードウェア・ノード上にインストール済みの Virtuozzo ライセンスの更新、ソース・ノードから宛先ノードへの Virtuozzo ライセンスの転送を行うユーティリティー。|
{: caption="表 2. ライセンス適用ユーティリティー" caption-side="top"}

## コンテナー・マイグレーション・ユーティリティー
{: #container-migration-utilities}

コンテナー・マイグレーション・ツールは、複数のハードウェア・ノード間や 1 つのハードウェア・ノード内でのコンテナーのマイグレーションに使用します。

|コンテナー・マイグレーション・ユーティリティー||
|---|---|
|vzmigrate|ハードウェア・ノード間でコンテナーをマイグレーションするユーティリティー。|
|vzmlocal|コンテナーをローカルで複製または移動するユーティリティー。|
|vzp2v|物理サーバーをノード上のコンテナーにマイグレーションするユーティリティー。|
|vzv2p|コンテナーを物理サーバーにマイグレーションするユーティリティー。|
{: caption="表 3. コンテナー・マイグレーション・ユーティリティー" caption-side="top"}

## コンテナー・バックアップ・ユーティリティー
{: #container-backup-utilities}

コンテナー・バックアップ・ユーティリティーは、コンテナーのプライベート領域、構成ファイル、アクション・スクリプト、割り当て量の情報のバックアップとリストアに使用します。

|コンテナー・バックアップ・ユーティリティー||
|---|---|
|vzbackup|コンテナーをバックアップするユーティリティー。|
|vzrestore|バックアップされたコンテナーをリストアするユーティリティー。|
|vzabackup|ハードウェア・ノードとそのコンテナーをバックアップするユーティリティー。 このユーティリティーには、Parallels Agent ソフトウェアが必要です。|
|vzarestore|バックアップされたハードウェア・ノードとコンテナーをリストアするユーティリティー。 このユーティリティーには、Parallels Agent ソフトウェアが必要です。|
{: caption="表 4. コンテナー・バックアップ・ユーティリティー" caption-side="top"}

## テンプレート管理ユーティリティー
{: #template-management-utilities}

テンプレート管理ツールは、テンプレートの作成、アプリケーションの保守、コンテナーへのアプリケーションのインストールに使用します。

|テンプレート管理ユーティリティー||
|---|---|
|vzpkg|コンテナー内またはハードウェア・ノード自体にある OS やアプリケーションの EZ テンプレートを管理するユーティリティー。|
|vzmktmpl|OS やアプリケーションの EZ テンプレートを作成するユーティリティー。|
|vzveconvert|Virtuozzo 標準テンプレートに基づくコンテナーを EZ テンプレート・ベースのコンテナーに変換するユーティリティー。|
|vzpkgproxy|OS やアプリケーションの EZ テンプレートを処理するためのキャッシング・プロキシー・サーバーを作成するユーティリティー。|
|vzrhnproxy|RHEL 4 と RHEL 5 の OS EZ テンプレートに含まれるパッケージを処理するための RHN プロキシー・サーバーを作成するユーティリティー。|
|vzpkgls|ハードウェア・ノード上やコンテナー内にあるテンプレートのリストを取得するユーティリティー。|
|vzpkginfo|ハードウェア・ノード上にインストールされているテンプレートに関する情報を取得するユーティリティー。|
|vzpkgcreat| バイナリー RPM または DEB ファイルから新しいパッケージ・セットを作成します。|
|vzpkgadd|テンプレートをコンテナーに追加するユーティリティー。|
|vzpkglink|コンテナー内の実ファイルを、ノード上のファイルに対するシンボリック・リンクに置換するユーティリティー。|
|vzpkgrm|テンプレートをコンテナーから削除するユーティリティー。|
|vzpkgcache|新しいテンプレートをインストールした後に、これまでインストールされていたコンテナー・アーカイブのセットを更新します。|
{: caption="表 5. テンプレート管理ユーティリティー" caption-side="top"}

## 補助ツール
{: #supplementary-tools}

ハードウェア・ノードやコンテナーに関連する各種タスクに使用できる補助ツールがあります。

|補助ツール||
|---|---|
|vzup2date|Virtuozzo のソフトウェアとテンプレートを更新するユーティリティー。|
|vzup2date-mirror|Virtuozzo オフィシャル・リポジトリーのローカル・ミラーを作成するユーティリティー。|
|vzfsutil|VZFS の最適化と整合性検査のためのユーティリティー。|
|vzcache|同一ファイルを別のコンテナーにキャッシュしてディスク・スペースを増やすユーティリティー。|
|vzsveinstall|ハードウェア・ノード上にサービス・コンテナーを作成するユーティリティー。|
|vzsveupgrade|サービス・コンテナー内のパッケージを更新するユーティリティー。|
|vzps|標準的な PS や TOP のユーティリティーの機能に加えてコンテナー関連の機能を備えたユーティリティー。|
|vztop|標準的な PS や TOP のユーティリティーの機能に加えてコンテナー関連の機能を備えたユーティリティー。|
|vzsetxinetd|一部のサービスのスタンドアロン・モードと `xinetddependent` モードを切り替えるユーティリティー。|
|vzdqcheck|割り当て量の観点からファイル・スペースの現在の使用量を出力します。|
|vzdqdump|カーネルまたはクォータ・ファイルからコンテナーのユーザーまたはグループの割り当て量限度や猶予時間をダンプしたりクォータ・ファイルにロードしたりするユーティリティー。|
|vzdqload|カーネルまたはクォータ・ファイルからコンテナーのユーザーまたはグループの割り当て量限度や猶予時間をダンプしたりクォータ・ファイルにロードしたりするユーティリティー。|
|vznetstat|コンテナー別のネットワーク・トラフィックの使用統計を出力するユーティリティー。|
|vzcpucheck|コンテナー別の CPU 使用率を検査するユーティリティー。|
|vzmemcheck|ハードウェア・ノードとコンテナーの現在のメモリー・パラメーターを検査するユーティリティー。|
|vzcalc|コンテナー別のリソース使用量を計算するユーティリティー。|
|vzcheckovr|現行システムのオーバーコミットおよび合計リソース制御設定の安全性を検査するユーティリティー。|
|vzstat|リアルタイムでハードウェア・ノードとコンテナーのリソース消費量をモニターするユーティリティー。|
|vzpid|プロセスが属するコンテナーの ID を出力するユーティリティー。|
|vzsplit|ハードウェア・ノードを均等に「分割」してコンテナー構成ファイルのサンプルを生成するユーティリティー。|
|vzcfgscale|コンテナー構成をスケーリングするユーティリティー。|
|vzcfgvalidate|コンテナー構成ファイルの正しさを検証するユーティリティー。|
|vzcfgconvert|Virtuozzo 2.0.2 コンテナー構成ファイルを Virtuozzo 2.5.x 形式に変換するユーティリティー。|
|vzstatrep|vzlmond によって収集されたログを分析し、それらのログに基づいて統計レポートを (テキスト形式とグラフ形式で) 生成するユーティリティー。|
|vzreport|問題報告を作成し、Parallels サポート・チームに自動的に送信するユーティリティー。|
|vzhwcalc|Linux サーバー上の主なリソースをスキャンし、その情報の指定場所にファイルを作成するユーティリティー。|
|vzveconvert|Virtuozzo 標準 OS テンプレートに基づくコンテナーを EZ テンプレート・ベースのコンテナーに変換するユーティリティー。|
|vznetcfg|ハードウェア・ノード上のネットワーク・デバイスを管理するユーティリティー。|
|vzmtemplate|インストール済みの OS とアプリケーションのテンプレートをハードウェア・ノード間でマイグレーションするユーティリティー。|
{: caption="表 6. 補助ツール" caption-side="top"}

## 一般用語
{: #common-terms}

|一般用語||
|---|---|
|ハードウェア・ノード|ハードウェア・ノード (HN) とは、コンテナーをホストする物理コンピューターです。|
|コンテナー|コンテナーは、機能的には、独立したスタンドアロン・サーバーと同じです。独自の IP アドレス、プロセス、ファイル、ユーザー、独自のバージョン、独自の構成ファイル、独自のアプリケーション、システム・ライブラリーなどのサーバー機能を持ちます。 複数のコンテナーでハードウェア・ノードや同じ OS カーネルを共有しますが、コンテナーは互いに独立しています。 各コンテナーに 1 から始まる数値の固有 ID が付けられます。|
|ホスト・オペレーティング・システム|ホスト・オペレーティング・システム (ホスト) とは、ハードウェア・ノード上にインストールされているオペレーティング・システムのことです。 実コンテナーが 1 から始まる ID を持つのに対し、ホストはコンテナー 0 とも呼ばれます。|
|テンプレート|テンプレート (またはパッケージ・セット) は、オリジナルのアプリケーション・ファイルのセットを、Virtuozzo File System (VZFS) 上にマウントするために再パッケージ化したものです。 Virtuozzo には 2 つのタイプのテンプレートがあります。コンテナーを新規作成する際にコンテナー・ベースで使用できる OS テンプレートと、コンテナーの作成後にコンテナーに追加できるアプリケーション・テンプレートです。|
|PIM|Parallels Infrastructure Manager (PIM) は、ホスト管理者のために設計された Web ベースの管理ツールです。|
|PMC|Parallels Management Console (PMC) は、ホスト管理者のために設計されたリモート管理ツールであり、グラフィカル・ユーザー・インターフェースを備えています。|
|PPP|Parallels Power Panel は、コンテナー所有者のために設計された Web ベースの管理ツールです。|
{: caption="表 7. 一般用語" caption-side="top"}