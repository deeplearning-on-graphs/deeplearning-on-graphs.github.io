<html lang="ja">
<head>
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.24/css/jquery.dataTables.css">
    <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
    <script type="text/javascript" src="https://cdn.datatables.net/1.10.24/js/jquery.dataTables.js"></script>
    <meta charset="UTF-8">
    <title>誤植情報</title>
<style>
    body {
        font-family: 'Verdana', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    h2 {
        color: #333;
    }
    table {
        width: 100%;
        max-width: 100%;
        border-collapse: collapse;
        margin-top: 20px; 
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    th, td {
        padding: 8px 10px;
        text-align: left;
        border-bottom: 1px solid #ddd;
        font-size: 14px;
    }
    th {
        background-color: #009879;
        color: #ffffff;
    }
    tr:hover {
        background-color: #f5f5f5;
    }
    </style>
</head>
<body>
  
<a href="./">メインページ</a>

<h2>誤植・修正情報</h2>
日本語訳にあたっては，最大限の努力をもって取り組んでおりますが，誤植や不正確な訳などが残っている可能性もございます．
<br>
現在判っている誤植・修正箇所は以下の通りです．

<h3>1刷〜</h3>

<table class="dataTables">
    <thead>
        <tr>
            <th>ページ</th>
            <th>誤</th>
            <th>正</th>
            <th>備考</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>p.8</td>
            <td>責任者にとっても有用であろう．．</td>
            <td>責任者にとっても有用であろう．</td>
            <td>誤植</td>
        </tr>
        <tr>
            <td>p.15<br>P193<br>P195</td>
            <td>Ma <em>et al</em>., 2020a</td>
            <td>Ma <em>et al</em>., 2019d</td>
            <td>修正</td>
        </tr>
        <tr>
            <td>p.90</td>
            <td>Paszke <em>et al</em>., 2017</td>
            <td>Paszke <em>et al</em>., 2019</td>
            <td>文献更新</td>
        </tr>
        <tr>
            <td>p.196</td>
            <td>ロバストなな</td>
            <td>ロバストな</td>
            <td>誤植</td>
        </tr>
        <tr>
            <td>p.200</td>
            <td>Tan <em>et al</em>., 2016</td>
            <td>Tan <em>et al</em>., 2021</td>
            <td>文献更新</td>
        </tr>
        <tr>
            <td>p.218</td>
            <td>重要度サンプリング</td>
            <td>重要度サンプリング(IS; Importance Sampling)</td>
            <td>修正</td>
        </tr>
        <tr>
            <td>p.303</td>
            <td>Han <em>et al</em>., 2011</td>
            <td>Han <em>et al</em>., 2022</td>
            <td>文献更新</td>
        </tr>
        <tr>
            <td>p.310</td>
            <td>Ying <em>et al</em>., 2018b</td>
            <td>Ying <em>et al</em>., 2018a</td>
            <td>修正</td>
        </tr>
        <tr>
            <td>p.331</td>
            <td>Nguyen <em>et al</em>., 2019</td>
            <td>Nguyen <em>et al</em>., 2020</td>
            <td>修正</td>
        </tr>
        <tr>
            <td>p.356</td>
            <td>Garey and Johnson, n.d.</td>
            <td>Garey and Johnson, n.d.</td>
            <td>修正</td>
        </tr>
        <tr>
            <td>p.360</td>
            <td>yuan <em>et al</em>.(2020)</td>
            <td>Yuan <em>et al</em>.(2020)</td>
            <td>誤植</td>
        </tr>
    </tbody>
</table>

<a href="./">メインページ</a>

</body>
<script>
$(document).ready(function() {
    $('.display').DataTable({
     "lengthChange": false,  // Show 10 entriesの選択機能を非表示にする
     "pageLength": 10000,  // ページごとに表示する行数を20行に設定
     "info": false,  // "Showing 1 to X of Y entries" の情報テキストを非表示にする
     "order": [],
     "searching": false
    });
});
</script>
</html>
