# きょうりゅう自由ぬりえ

4歳くらいから遊べる、iPhone対応の恐竜ぬりえWebサイトです。

## 今回の重要な修正
- iPhone Safariでの塗り操作を `pointerdown` 依存から `click` に変更し、タップで確実に発火するよう修正。
- SVGの塗り領域に `fill="#fff"` を明示し、色選択→タップ→塗りつぶしを安定化。
- `pointer-events:all` と `touch-action:none` を設定。
- 恐竜の輪郭を以前の単純な多角形から、頭部・顎・首・胴体・尾・脚などの形状をより自然な曲線で構成。
- 10種類の恐竜を選択可能。
- 23色を自由に選択可能。
- Undo / Reset / Clear / Preview 対応。

## GitHub Pages
`index.html` をリポジトリ直下に置き、Settings → Pages → Deploy from a branch → main → /(root) を選択してください。
