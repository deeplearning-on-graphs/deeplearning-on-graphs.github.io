<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>PDFの埋め込み表示</title>
    <style>
        #iframeBlock{
            height: 100%;
        /* iframeのサイズ調整 */
        .iframeBody{
            height: 100%;
        iframe {
            border: none; /* 枠線を非表示に */
            width: 100%;
            height: 830px;
        }
        }
            }
    </style>
</head>
<body>

<h2>参考文献（PDF）</h2>

<!-- PDFファイルの埋め込み表示 -->
<div id="iframeBlock">
    <div class="iframeBody">
    <iframe src="https://deeplearning-on-graphs.github.io/References.pdf"></iframe>
    </div>
</div>

</body>
</html>
