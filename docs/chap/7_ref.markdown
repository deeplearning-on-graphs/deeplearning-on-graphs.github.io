
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>参考文献リスト</title>
<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.24/css/jquery.dataTables.css">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.24/js/jquery.dataTables.js"></script>
<style>
    body {
        font-family: 'Verdana', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
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
        font-size: 11px;
    }
    th {
        background-color: #009879;
        color: #ffffff;
    }
    tr:hover {
        background-color: #f5f5f5;
    }
    /* 1番目の列の幅を70%に設定 */
    table.display td:nth-child(1),
    table.display th:nth-child(1) {
        width: 70%;
    }

    /* 2番目の列の幅を25%に設定 */
    table.display td:nth-child(2),
    table.display th:nth-child(2) {
        width: 25%;
    }

</style>
</head>
<body>

<a href="../">メインページ</a>

<h3>7.1節 はじめに</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>登場順</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Stochastic Training of Graph Convolutional Networks with Variance Reduction</td>
      <td>Chen et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1710.10568" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling</td>
      <td>Chen et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1801.10247" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Adaptive Sampling Towards Fast Graph Representation Learning</td>
      <td>Huang et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1809.05343" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
  </tbody>
</table>
<h3>7.2節 ノードサンプリング</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>登場順</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Stochastic Training of Graph Convolutional Networks with Variance Reduction</td>
      <td>Chen et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1710.10568" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
  </tbody>
</table>
<h3>7.3節 層サンプリング</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>登場順</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling</td>
      <td>Chen et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1801.10247" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Adaptive Sampling Towards Fast Graph Representation Learning</td>
      <td>Huang et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1809.05343" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Monte Carlo Theory, Methods and Examples</td>
      <td>Owen</td>
      <td>2013</td>
      <td><a href="https://artowen.su.domains/mc/" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
  </tbody>
</table>
<h3>7.4節 部分グラフサンプリング</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>登場順</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks</td>
      <td>Chiang et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1905.07953" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>GraphSAINT: Graph Sampling Based Inductive Learning Method</td>
      <td>Zeng et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1907.04931" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>A fast and high quality multilevel scheme for partitioning irregular graphs</td>
      <td>Karypis and Kumar</td>
      <td>1998</td>
      <td><a href="https://glaros.dtc.umn.edu/gkhome/node/107" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Weighted Graph Cuts without Eigenvectors: A Multilevel Approach</td>
      <td>Dhillon et al</td>
      <td>2007</td>
      <td><a href="https://www.cs.utexas.edu/users/inderjit/public_papers/multilevel_pami.pdf" target="_blank">PDF</a></td>
      <td>4</td>
    </tr>
  </tbody>
</table>
<h3>7.6節 発展的な話題</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>登場順</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Graph Convolutional Neural Networks for Web-Scale Recommender Systems</td>
      <td>Ying et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1806.01973" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling</td>
      <td>Chen et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1801.10247" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics</td>
      <td>Weber et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1908.02591" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Towards Efficient Large-Scale Graph Neural Network Computing</td>
      <td>Ma et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1810.08403" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Deep Graph Library: A Graph-Centric, Highly-Performant Package for Graph Neural Networks</td>
      <td>Wang et al</td>
      <td>2019e</td>
      <td><a href="https://arxiv.org/abs/1909.01315" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>AliGraph: A Comprehensive Graph Neural Network Platform</td>
      <td>Zhu et al</td>
      <td>2019c</td>
      <td><a href="https://arxiv.org/abs/1902.08730" target="_blank">arxiv</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>NeuGraph: Parallel Deep Neural Network Computation on Large Graphs</td>
      <td>Ma et al</td>
      <td>2019a</td>
      <td><a href="https://www.usenix.org/conference/atc19/presentation/ma" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
  </tbody>
</table>

<script>
$(document).ready(function() {
    $('.display').DataTable({
     "lengthChange": false,  // Show 10 entriesの選択機能を非表示にする
     "pageLength": 25,  // ページごとに表示する行数を20行に設定
     "info": false,  // "Showing 1 to X of Y entries" の情報テキストを非表示にする
     "order": [],
     "searching": false
    });
});
</script>

<a href="../">メインページ</a>

</body>
</html>