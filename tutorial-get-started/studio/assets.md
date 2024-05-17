# アセット

## アセットとは
アセットとは、PitWallで利用する各サイト（Webページ、監視ツールなど）へのアクセスと検索条件を事前定義し、登録しておくことができます。Assetをつかうことで、再利用性を高めることができます。

## 使用方法

初期画面
はじめて利用する場合、このような画面になります。

<figure><img src="../../.gitbook/assets/AssetsPageInitial_jp.png" width="50%" alt="アセット初期ページ"></figure>

### アセットの登録
右上の「アセットの新規作成」ボタンをクリックします。

#### アセット情報の入力
モーダル画面の 「#1 アセット情報の入力」 からAssetの識別情報を登録します。<!--Photo--> 
<figure><img src="../../.gitbook/assets/RegisterAssets_jp.png" width="50%" alt="アセット情報入力"></figure>

- 名前: このアセットを素早く見つけられるように任意の名前をつけます。
- カテゴリー: 対象アセットをふくむ同種のアセットを仕分けるための任意のカテゴリ名を定義します。（例：Trace, Log, Metricなど）
  - 任意のカテゴリー名を入力後、ポップアップされる「Add *カテゴリー名* ...」をクリックして、カテゴリー名を確定させる必要があります。
  - カテゴリー名を登録した場合、初期画面のヘッダにタブとして表示されます。
- チーム: PitWallを複数のチームで利用する場合や利用シーンが異なるなどの場合に分類をするために利用します。
  - 任意のチーム名を入力後、ポップアップされる「Add *チーム名* ...」をクリックして、チーム名を確定させる必要があります。
- URL: このAssetからアクセスする先のWebサービスのURLを登録します。
- 自動検出されたサービス: URL欄に登録した情報を元に「拡張機能」に登録されているURLからこのAssetに紐づくExtensionがある場合に自動検出します。初期状態では、「コミュニティ拡張機能」に登録されているWebサービスがある場合、自動検出されます。それ以外については、ユーザが個別に「プライベート拡張機能」に登録したモノが利用可能です。

「次のページ」ボタンをクリックします。

### スクリーンショット設定を構成
<!--Photo-->
<figure><img src="../../.gitbook/assets/RegisterAssetsScreenshot_jp.png" width="50%" alt="スクリーンショット設定"></figure>

Assetのスクリーンショットを取得するかどうかについて確認します。
下記のいづれかを選択します。

- はい、スクリーンショットを撮ります。
- いいえ、スクリーンショットは必要ありません。

スクリーンショットを取得する場合：

「はい、スクリーンショットを撮ります。」を選択します。

- Use an existing screenshot option
- Create new screenshot option

スクリーンショットを取得しない場合：

「いいえ、スクリーンショットは必要ありません。」を選択します。
「次のページ」ボタンをクリックします。
スクリーンショットをとらないことを確認する画面が表示されますので、「保存」ボタンをクリックします。
登録完了の画面が表示されアセットの登録完了となります。完了ボタンで初期画面に戻ります。
<!--Photo--> 
<figure><img src="../../.gitbook/assets/RegisterAssetscomplete_jp.png" width="50%" alt="アセット登録完了"></figure>


### Assetの確認
アセットの登録が完了したら、アセット一覧に登録したアセットが表示されているかを確認します。
<!--Photo--> 
<figure><img src="../../.gitbook/assets/RegisterAssetsList_jp.png" width="50%" alt="登録確認"></figure>

### Assetの削除

作成したAssetは、右サイドの三点リーダ![](../../.gitbook/assets/three_points_reader_icon.png)より"Delete this asset"を選択します。
削除してよい場合、削除ボタンをクリックして確定させます。
<!--Photo--> 
<figure><img src="../../.gitbook/assets/RegisterAssetsDelete_jp.png" width="50%" alt="登録削除"></figure>