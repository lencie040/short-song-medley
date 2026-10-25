# ショートソングメドレー

TurboWarp で作った自作ミュージックプレイヤーを、ブラウザでそのまま遊べる HTML にしたものです。

▶ 公開ページ: `https://<ユーザー名>.github.io/<リポジトリ名>/`

## 構成

- `index.html` / `script.js` — TurboWarp Packager で書き出したプレイヤー本体
- `assets/` — プロジェクトデータ（`project.json`）と画像・音声ファイル
- `.nojekyll` — GitHub Pages でそのまま配信するための設定

## 作り直し方

`ショートソングメドレー.sb3` を [TurboWarp Packager](https://packager.turbowarp.org/) で
「Zip（アセットを別ファイルにする）」形式で書き出し、中身をこのフォルダに上書きしてください。
