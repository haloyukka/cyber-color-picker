# Cyber Color Picker

ネオン発光のサイバーパンクデザインを持つ、単一HTMLのカラーピッカーです。

**Live:** https://haloyukka.github.io/cyber-color-picker/

## Features
- 彩度/明度エリア＋色相・アルファスライダー
- HEX / RGB(A) / HSL(A) / HSV / CMYK / OKLCH / LAB / CSS色名の相互変換（どの欄にも任意形式で入力可）
- スポイト（EyeDropper API: Chrome/Edge）、画像からの色取得（ドラッグ＆ドロップ対応）
- 配色パレット（補色・類似色・トライアド・スプリット補色・テトラド）と 50–900 の濃淡シェード
- WCAG コントラストチェック（AA / AA Large / AAA）
- 履歴（30件）・お気に入り（100件）を localStorage に保存
- CSS変数 / JSON / Tailwind 設定の書き出し、PNG保存、URLハッシュでの共有
- ダーク / ライト切替（初期値は OS 設定に追従）、レスポンシブ、キーボード操作対応

## Usage
`index.html` をブラウザで開くだけで動作します。ビルド不要・外部依存は Web フォントのみです。
