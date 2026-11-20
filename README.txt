味噌ができるまで — 完成版

■ 起動方法
1. このフォルダを VS Code で開く
2. Live Server で index.html を開く
3. インターネット接続を有効にする（GSAP / ScrollTrigger / Lottie Web と Web フォントを CDN から読み込みます）

■ 主なファイル
- index.html       ページ構造・コンテンツ
- styles.css       レイアウト・デザイン
- functions.js     クイズ、地図、スクロール連動演出
- lottie/bowl.json お椀のアニメーション
- lottie/taru.json 樽のアニメーション
- assets/          配布キットの画像・SVG・Illustrator素材

■ GitHub / Vercel
このフォルダ内の index.html, styles.css, functions.js, assets/, lottie/ をリポジトリのルートに置いて push すると、Vercel から公開できます。

■ 補足
お椀・樽のLottie JSONは配布されたIllustrator素材をもとに生成したWeb用アニメーションです。授業PDFにあるAfter Effectsでの全キーフレーム編集とLottie Creatorによる書き出し工程を再現した.aepファイルではありません。
