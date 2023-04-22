# pandoc-sidenote.js

`pandoc-sidenote.js` is a simple Pandoc filter that converts footnotes to side notes or margin notes in HTML documents. It is inspired by [`pandoc-sidenote`](https://github.com/jez/pandoc-sidenote) by Jacob Zimmerman et al. and implemented in JavaScript.This filter automatically converts URLs to links as an enhancement over the original version.

## Usage

To use the filter, simply run:

```shell
pandoc --filter pandoc-sidenote.js
```

For the side note syntax information, please refer to the [documentation](https://jez.io/pandoc-markdown-css-theme/features/#side-notes-and-margin-notes) written for [pandoc-markdown-css-theme](https://github.com/jez/pandoc-markdown-css-theme). To test the filter, I recommend using the tool (modifying the `build.sh` script in the `tools` folder is necessary).

## Acknowledgments

I would like to express my gratitude to the developers of the original [pandoc-sidenote](https://github.com/jez/pandoc-sidenote) developers and the Pandoc team for their great work on creating and maintaining these projects.

---

`pandoc-sidenote.js`は、HTML文書内の脚注を傍注（side note：番号あり・margin note：番号なし）に変換するシンプルなPandocフィルターです。Jacob Zimmermanらによる[`pandoc-sidenote`](https://github.com/jez/pandoc-sidenote)から着想を得てJavaScriptで実装されています。オリジナル版からの機能拡張として、URLを自動的にリンクに変換します。

## 使い方

フィルターを使用するには、次のコマンドを実行します:

```shell
pandoc --filter pandoc-sidenote.js
```

傍注の記法については、[`pandoc-markdown-css-theme`](https://github.com/jez/pandoc-markdown-css-theme)の[ドキュメント](https://jez.io/pandoc-markdown-css-theme/features/#side-notes-and-margin-notes)を参照してください。フィルターの動作を確認するには、このテンプレートを使用することをおすすめします（`tools`フォルダにある`build.sh`の書き換えが必要です）。

## 謝辞

オリジナル版の[pandoc-sidenote](https://github.com/jez/pandoc-sidenote)開発者およびPandocチームに対して、素晴らしいツールの作成および維持に関する尽力に、心から感謝と尊敬の意を表します。
