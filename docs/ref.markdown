<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- スマホ対応のビューポート設定を追加 -->
    <title>PDFの埋め込み表示</title>
<style>
    .iframe-wrap {
        overflow: auto; /* スクロールを可能にする */
        -webkit-overflow-scrolling: touch; /* iOSデバイスでのスムーズなスクロールを有効にする */
        height: 100vh; /* ビューポートの高さに合わせる */
        border: none;
    }
    .iframe-wrap iframe {
        width: 100%; /* コンテナの幅に合わせる */
        height: 100%; /* スクロールを有効にするため、高さを指定 */
    }
</style>
</head>
<body>

<h2>参考文献（PDF）</h2>
<!-- PDFファイルの埋め込み表示 -->
<div class="iframe-wrap">
    <iframe src="https://deeplearning-on-graphs.github.io/References.pdf" allow="fullscreen"></iframe>
</div>

</body>
</html>
