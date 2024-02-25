<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>PDFの埋め込み表示</title>
    <style>
        .iframe-wrap iframe {
            aspect-ratio: 16 / 9;
            width: 100%;
            height: 100%;
            border: none;
        }
        .iframe-wrap {
            position: relative;
            width: 100%;
            padding-top: 56.25%; /* 16:9のアスペクト比 */
        }
        /*iframe {
            position: absolute;
            top: 0;
            left: 0;
        } */
    </style>
</head>
<body>

<h2>参考文献（PDF）</h2>
本書で参照されている論文・書籍をまとめています。原著の出版当時(2021年9月)の情報をそのまま載せていますので、記載している内容からアップデートされている可能性がございます。
引用文を転載するときなどはご注意ください。

<!--CSV形式でもご用意しておりますのでご自由にお使いください(<a href="" target="_blank">CSV形式はこちら</a>)。-->
<!-- PDFファイルの埋め込み表示 -->
<div class="iframe-wrap">
<!--<iframe src="http://docs.google.com/gview?embedded=true&url=https://deeplearning-on-graphs.github.io/References.pdf"></iframe>-->
<iframe src="https://deeplearning-on-graphs.github.io/References.pdf"></iframe>
</div>
</body>
</html>


[メインページ](index.markdown)
