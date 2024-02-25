<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>PDFの埋め込み表示</title>
    <script src="//mozilla.github.io/pdf.js/build/pdf.js"></script>
    <style>
        #canvas-container {
            width: 100%;
            text-align: center;
        }
        canvas {
            width: 100%;
            border: 1px solid black;
        }
    </style>
</head>
<body>

<h2>参考文献（PDF）</h2>
<div id="canvas-container">
    <canvas id="pdf-canvas"></canvas>
</div>
<button id="prev">前のページ</button>
<button id="next">次のページ</button>
<span id="page_num"></span> / <span id="page_count"></span>

<script>
    var url = 'https://deeplearning-on-graphs.github.io/References.pdf';

    let pdfDoc = null,
        pageNum = 1,
        pageIsRendering = false,
        pageNumIsPending = null;

    const scale = 1.5,
          canvas = document.getElementById('pdf-canvas'),
          ctx = canvas.getContext('2d');

    // PDFを読み込む
    pdfjsLib.getDocument(url).promise.then(pdfDoc_ => {
        pdfDoc = pdfDoc_;
        document.getElementById('page_count').textContent = pdfDoc.numPages;
        renderPage(pageNum);
    });

    // ページをレンダリングする
    const renderPage = num => {
        pageIsRendering = true;

        // ページを取得する
        pdfDoc.getPage(num).then(page => {
            // ビューポートを設定する
            const viewport = page.getViewport({scale: scale});
            canvas.height = viewport.height;
            canvas.width = viewport.width;

            const renderCtx = {
                canvasContext: ctx,
                viewport: viewport
            };

            page.render(renderCtx).promise.then(() => {
                pageIsRendering = false;

                if (pageNumIsPending !== null) {
                    renderPage(pageNumIsPending);
                    pageNumIsPending = null;
                }
            });

            // 現在のページ番号を表示する
            document.getElementById('page_num').textContent = num;
        });
    };

    // 前のページを表示する
    document.getElementById('prev').addEventListener('click', () => {
        if (pageNum <= 1) {
            return;
        }
        pageNum--;
        renderPage(pageNum);
    });

    // 次のページを表示する
    document.getElementById('next').addEventListener('click', () => {
        if (pageNum >= pdfDoc.numPages) {
            return;
        }
        pageNum++;
        renderPage(pageNum);
    });
</script>

</body>
</html>
