<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- スマホ対応のビューポート設定を追加 -->
    <title>PDFの埋め込み表示</title>
    <style>
        .iframe-wrap {
            position: relative;
            overflow: hidden;
            width: 100%;
            /* パディングトップを16:9のアスペクト比から動的に計算するように変更する */
            padding-top: 56.25%; /* 16:9 Aspect Ratio */
        }

        .iframe-wrap iframe {
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            width: 100%;
            height: 100%;
            border: none;
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
