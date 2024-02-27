<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>PDFの埋め込み表示</title>
    <style>
        .iframe-wrap {
            position: relative;
            overflow: auto; /* コンテナでのスクロールを有効にする */
            width: 100%;
            height: 110vh; /* ビューポートの高さの80%を高さとする */
        }
        .iframe-wrap iframe {
            width: 100%; /* コンテナの幅に合わせる */
            height: 100%; /* スクロールを考慮した高さ設定 */
            border: none;
        }
    </style>
</head>
<body>
<a href="./">メインページ</a>

<h2>参考文献（PDF）</h2>
本書で参照されている論文・書籍をまとめています．
原著の出版当時(2021年9月)の情報をそのまま載せていますので，記載している内容からアップデートされている可能性がございます．
引用文を転載するときなどはご注意ください．
PDFは以下をご確認ください．

<!-- PDFファイルの埋め込み表示 -->
<div class="iframe-wrap">
    <iframe src="https://deeplearning-on-graphs.github.io/References.pdf" allow="fullscreen"></iframe>
</div>
<br>
<a href="./">メインページ</a>
</body>
</html>
