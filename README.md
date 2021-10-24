# Log2Console

## 日本語の文字化け対応
Log2Console は、NLog、Log4net、Log4jなどのさまざまなログサービスからのログメッセージをリアルタイムに表示し、フィルタリング・検索機能も備えた素晴らしい開発ツールです。

しかし、詳細メッセージの日本語が文字化けしてしまうため、その能力を十分に発揮できるように文字化けを改修しました。

## 主な特徴

詳細は、[オリジナルの説明](Readme_org.md)を参照してください。

## 日本語対応

オリジナル
![オリジナル](docs/Localizing_Original.png)

日本語対応版
![日本語化](docs/Localizing_Japanese.png)

### 制限事項
Visual Studio 2019に移植後、WinDebug(OutputDebugString)の
受信機能はハングするため、削除しました。

また、セットアップ機能も未対応のため削除しました。
適当なフォルダに置いて使ってください。

## Download
[Latest Release] https://github.com/sabakunotabito/log2console/releases
