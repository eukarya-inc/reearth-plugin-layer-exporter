# Layer Expoter プラグイン

![test reearth dev_published html_alias=dbajbgegie(1440 desktop) (1)](https://user-images.githubusercontent.com/21994748/183613180-3a4050d5-9627-41b3-9368-cc72c6b98812.png)

<img width="1383" alt="WX20220809-171914@2x" src="https://user-images.githubusercontent.com/21994748/183613199-4bb42074-1fdd-43e5-b228-8130fbd496d5.png">

## このプラグインについて
- Layer Exporter プラグインではレイヤー情報をファイルに出力することができます。<br>
- このプラグインは[reearth-plugin-toolbox](https://github.com/airslice/reearth-plugin-toolbox)を利用して作成されています。

　
## 使用方法
### 編集ページでの設定項目
編集ページにおいて、プラグインの右パネルでは以下の項目を設定することができます。
- Customize
  - Theme：ウィジェットのテーマカラーをDarkかLightから選択することができます。
  - Backgroung Color：ウィジェットの背景色を変更することができます。これを設定している場合、Themeの設定内容は無視されます。
  - Primary Color：Exportボタンの色を変更することができます。これを設定している場合、Themeの設定内容は無視されます。
    ![](https://eukarya-inc.github.io/reearth-plugin-layer-exporter/src/img1.png)

    (左：ThemeをDark、中央：ThemeをLight、右：BackgroundColorとPrimary Colorを指定)
    ![](https://eukarya-inc.github.io/reearth-plugin-layer-exporter/src/img2.png)

### プラグインの操作方法
  ![](https://eukarya-inc.github.io/reearth-plugin-layer-exporter/src/img4.png)
- Exportボタンを押すとレイヤーの情報をCSVファイルとして書き出します。出力されるCSVファイルの内容にはレイヤ名、経度、緯度などの情報の他、右パネルで設定した項目内容が出力されます。
  
  ![](https://eukarya-inc.github.io/reearth-plugin-layer-exporter/src/img3.png)

- ファイル名は reearth-layers-xxxxxxx.csvの形式で作成されます。

### 留意点
- 現状、出力ファイル形式は.csvのみサポートしています。


## 備考
- テストブラウザ環境
  - OS:Mac OS Montery 12.6.5
  - ブラウザ：Google Chrome 112.0.5615.121

## 開発者欄

このプラグインは、Re:Earth公式プラグインです。

 ![](https://eukarya-inc.github.io/reearth-plugin-layer-exporter/src/logo-3.png)

ソースコードはこちら(https://github.com/airslice/reearth-plugin-layer-exporter)

- コミュニティ

  - このプラグインを利用したプロジェクトをユーザーコミュニティでシェアしましょう。

  - このプラグインについての不明点がある場合にもここからRe:Earthチームや他の開発者に質問することができます。

  - Discordへのリンクはこちら(https://discord.gg/BXcQhvwqqM)


