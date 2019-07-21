# Firebird DBMS 日本語マニュアル

本ドキュメントは日本ではあまり流行っていない（__もっと流行っていいのだけれどなあ__）データベース [Firebird](https://firebirdsql.org/) のマニュアルを翻訳したものです。

一応[Firebird日本ユーザ会](http://tech.firebird.gr.jp/firebird/index.php?firebird_xsite=0) はあるみたいなのですが、あまり活動しているように見えなかったので、少しずつ日本語化していこうかなと思い立った次第です。

----

なお、本ドキュメントの作成には[gitbook-cli](https://www.npmjs.com/package/gitbook-cli)をフォークした[@aleung/gitbook](https://www.npmjs.com/package/@aleung/gitbook)を使用しています。GitBook自体はSaasに注力するとのことで、``gitbook-cli``はメンテナンスされていないため、これをなんとかしようとしたのが``@aleung/gitbook``です（まあこれでも、脆弱性は残っていますが）。Markdownとnodeを使ってサクサクドキュメントを書こうとしたとき、これが一番使いやすいです。

リポジトリからクローンした後は、以下の手順でマニュアルを参照できます。

* 依存性を解決します。

``` bash
$ npm install
# または
$ yarn
```

* gitbook-cliのプラグインを導入します。

``` bash
$ npm run install
# または
$ yarn run install
```

* HTTPサーバを起動してマニュアルを参照することができます。

``` bash
$ npm run serve
# または
$ yarn run serve
```

* または、配置可能な静的ファイルを``_book``ディレクトリに出力します。

``` bash
$ npm run build
# または
$ yarn run build
```
