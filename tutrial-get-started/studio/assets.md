# Asset

## Assetとは
Assetとは、PitWallで利用する各サイト（Webページ、監視ツールなど）へのアクセスと検索条件を定義し、登録しておくことができます。Assetをつかうことで、再利用性を高めることができます。

## 使用方法

初期画面
はじめて利用する場合、このような画面になります。

{photo}

### Assetの登録
右上のAdd a new Assetボタンをクリックします。

#### Fullfill the asset profile
モーダル画面の #1 Fullfill the asset profile からAssetの識別情報を登録します。

{photo}

- name: このAssetを素早く見つけられるように任意の名前をつけます。
- Category: 対象Assetをふくむ同種のAssetを仕分けるための任意のカテゴリ名を定義します。（例：Trace, Log, metricなど）
  - カテゴリ名を登録した場合、初期画面のヘッダにタブとして表示されます。
- Team: PitWallを複数のチームで利用する場合や利用シーンが異なるなどの場合に分類をするために利用します。
- URL: このAssetからアクセスする先のWebサービスのURLを登録します。
- Service automaticall detected: Extensionsに登録されているURLからこのAssetに紐づくExtensionがある場合に自動検出します。初期状態では、Community extensionsに登録されているWebサービスがある場合、自動検出されます。

Nextボタンをクリックします。

### Configure screenshot setting
Assetのスクリーンショットを取得するかどうかについて確認します。
下記のいづれかを選択します。
- Yes, take a screenshot.
- No, a screenshot is not needed.

取得する場合：
"Yes, take a screenshot."を選択します。

- Use an existing screenshot option
- Create new screenshot option

取得しない場合：
"No, a screenshot is not needed."を選択します。
Nextボタンをクリックし、登録完了となります。


### Assetの確認



### Assetの削除

