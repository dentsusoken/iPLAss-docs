# iPLAss ドキュメント

iPLAss 技術ドキュメントを管理するプロジェクトです。

### ディレクトリ構成

```txt
iPLAss-docs/
├─developerguide/     ドキュメント DEVELOPE RGUIDE の Asciidoc ファイルを管理します
├─environment/        ドキュメント ENVIRONMENT の Asciidoc ファイルを管理します
├─eqlreference/       ドキュメント EQL REFERENCE の Asciidoc ファイルを管理します
├─gettingstarted/     ドキュメント GETTING STARTED の Asciidoc ファイルを管理します
├─gradle/             Gradle Runtime を格納
├─overview/           ドキュメント OVERVIEW の Asciidoc ファイルを管理します
├─sample/             ドキュメント SAMPLE の Asciidoc ファイルを管理します
├─serviceconfig/      ドキュメント CONFIGURATION の Asciidoc ファイルを管理します
├─src/
│  └─docs/
│      └─asciidoc/    ドキュメントトップページの Asciidoc ファイルを管理します
└─build/
    └─asciidoc/       asciidoctor コマンドでビルドされた結果の HTML ファイルが格納されます。

```

### HTMLファイル生成
asciidoc ドキュメントを asciidoctorj を利用して HTML5 形式に出力します。

### HTMLファイル生成コマンド

#### 日本語
`gradlew asciidoctor`

#### 英語
`gradlew -Pasciidoc_lang="en" asciidoctor`


### plugin について

* asciidoctor gradle plugin
    * [説明 ルートページ](https://asciidoctor.github.io/asciidoctor-gradle-plugin/)
    * [説明 ユーザーガイド](https://asciidoctor.github.io/asciidoctor-gradle-plugin/development-3.x/user-guide/)
    * [github](https://github.com/asciidoctor/asciidoctor-gradle-plugin)
* asciidoctorj
    * [github](https://github.com/asciidoctor/asciidoctorj)

### License

The contents of this repository, except for all image files and their source files, are licensed under CC BY-SA 4.0.
Images and their source files in this repository retain the copyright and licensing terms of their respective authors and owners.
