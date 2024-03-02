
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
        font-size: 11px;
    }
    th {
        background-color: #009879;
        color: #ffffff;
    }
    tr:hover {
        background-color: #f5f5f5;
    }
    /* 1番目の列の幅を60%に設定 */
    table.display td:nth-child(1),
    table.display th:nth-child(1) {
        width: 60%;
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

<h3>9.1節 はじめに</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Structural Deep Network Embedding</td>
      <td>Wang et al</td>
      <td>2016</td>
      <td><a href="https://dl.acm.org/doi/10.1145/2939672.2939753" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Variational Graph Auto-Encoders</td>
      <td>Kipf and Welling</td>
      <td>2016b</td>
      <td><a href="https://arxiv.org/abs/1611.07308" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Adversarially Regularized Graph Autoencoder for Graph Embedding</td>
      <td>Pan et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1802.04407" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>GraphGAN: Graph Representation Learning with Generative Adversarial Nets</td>
      <td>Wang et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1711.08267" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>GraphVAE: Towards Generation of Small Graphs Using Variational Autoencoders</td>
      <td>Simonovsky and Komodakis</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1802.03480" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>MolGAN: An implicit generative model for small molecular graphs</td>
      <td>De Cao and Kipf</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1805.11973" target="_blank">arxiv</a></td>
      <td>6</td>
    </tr>
  </tbody>
</table>
<h3>9.2節 グラフ上のオートエンコーダー</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Structural Deep Network Embedding</td>
      <td>Wang et al</td>
      <td>2016</td>
      <td><a href="https://dl.acm.org/doi/10.1145/2939672.2939753" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Variational Graph Auto-Encoders</td>
      <td>Kipf and Welling</td>
      <td>2016b</td>
      <td><a href="https://arxiv.org/abs/1611.07308" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Adversarially Regularized Graph Autoencoder for Graph Embedding</td>
      <td>Pan et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1802.04407" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
  </tbody>
</table>
<h3>9.3節 グラフ上のRNN</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks</td>
      <td>Tai et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1503.00075" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Semantic Object Parsing with Graph LSTM</td>
      <td>Liang et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1603.07063" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<h3>9.4節 グラフ上のVAE</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Auto-Encoding Variational Bayes</td>
      <td>Kingma and Welling</td>
      <td>2013</td>
      <td><a href="https://arxiv.org/abs/1312.6114" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Variational Graph Auto-Encoders</td>
      <td>Kipf and Welling</td>
      <td>2016b</td>
      <td><a href="https://arxiv.org/abs/1611.07308" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>GraphVAE: Towards Generation of Small Graphs Using Variational Autoencoders</td>
      <td>Simonovsky and Komodakis</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1802.03480" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Finding Matches in a Haystack: A Max-Pooling Strategy for Graph Matching in the Presence of Outliers</td>
      <td>Cho et al</td>
      <td>2014b</td>
      <td><a href="https://inria.hal.science/hal-01053675" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
  </tbody>
</table>
<h3>9.5節 グラフ上のGAN</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Generative Adversarial Nets</td>
      <td>Goodfellow et al</td>
      <td>2014a</td>
      <td><a href="https://arxiv.org/abs/1406.2661" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>GraphGAN: Graph Representation Learning with Generative Adversarial Nets</td>
      <td>Wang et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1711.08267" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Hierarchical Probabilistic Neural Network Language Model</td>
      <td>Morin and Bengio</td>
      <td>2005</td>
      <td><a href="https://proceedings.mlr.press/r5/morin05a.html" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Distributed Representations of Words and Phrases and their Compositionality</td>
      <td>Mikolov et al</td>
      <td>2013</td>
      <td><a href="https://arxiv.org/abs/1310.4546" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>MolGAN: An implicit generative model for small molecular graphs</td>
      <td>De Cao and Kipf</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1805.11973" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
  </tbody>
</table>
<h3>9.7節 参考文献</h3>
<table class="dataframe display">
  <thead>
    <tr style="text-align: right;">
      <th>タイトル</th>
      <th>著者名</th>
      <th>年</th>
      <th>リンク</th>
      <th>節内順序</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Junction Tree Variational Autoencoder for Molecular Graph Generation</td>
      <td>Jin et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1802.04364" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders</td>
      <td>Ma et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1809.02630" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation</td>
      <td>You et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1806.02473" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models</td>
      <td>You et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1802.08773" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Efficient Graph Generation with Graph Recurrent Attention Networks</td>
      <td>Liao et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1910.00760" target="_blank">arxiv</a></td>
      <td>5</td>
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