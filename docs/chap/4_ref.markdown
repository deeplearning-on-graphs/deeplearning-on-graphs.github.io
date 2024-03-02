
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

<h3>4.1節 はじめに</h3>
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
      <td>DeepWalk: Online Learning of Social Representations</td>
      <td>Perozzi et al</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1403.6652" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>LINE: Large-scale Information Network Embedding</td>
      <td>Tang et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1503.03578" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>node2vec: Scalable Feature Learning for Networks</td>
      <td>Grover and Leskovec</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1607.00653" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>struc2vec: Learning Node Representations from Structural Identity</td>
      <td>Ribeiro et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1704.03165" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Preserving Local and Global Information for Network Embedding</td>
      <td>Ma et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1710.07266" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>PRUNE: Preserving Proximity and Global Ranking for Network Embedding</td>
      <td>Lai et al</td>
      <td>2017</td>
      <td><a href="https://proceedings.neurips.cc/paper/2017/hash/cdd96eedd7f695f4d61802f8105ba2b0-Abstract.html" target="_blank">リンク</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>RaRE: Social Rank Regulated Large-scale Network Embedding</td>
      <td>Gu et al</td>
      <td>2018</td>
      <td><a href="https://dl.acm.org/doi/abs/10.1145/3178876.3186102" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Community Preserving Network Embedding</td>
      <td>Wang et al</td>
      <td>2017c</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/10488" target="_blank">リンク</a></td>
      <td>8</td>
    </tr>
  </tbody>
</table>
<h3>4.2節 単純グラフのグラフ埋め込み</h3>
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
      <td>DeepWalk: Online Learning of Social Representations</td>
      <td>Perozzi et al</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1403.6652" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>node2vec: Scalable Feature Learning for Networks</td>
      <td>Grover and Leskovec</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1607.00653" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>LINE: Large-scale Information Network Embedding</td>
      <td>Tang et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1503.03578" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Random-Walk Computation of Similarities between Nodes of a Graph with Application to Collaborative Recommendation</td>
      <td>Fouss et al</td>
      <td>2007</td>
      <td><a href="https://www.semanticscholar.org/paper/Random-Walk-Computation-of-Similarities-between-of-Fouss-Pirotte/474db64356d6c9c82fe2a8604cd6c13bc17bae78" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Local Graph Partitioning using PageRank Vectors</td>
      <td>Andersen et al</td>
      <td>2006</td>
      <td><a href="https://www.cs.cmu.edu/afs/cs/user/glmiller/public/Scientific-Computing/F-11/RelatedWork/local_partitioning_full.pdf" target="_blank">PDF</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>Distributed Representations of Words and Phrases and their Compositionality</td>
      <td>Mikolov et al</td>
      <td>2013</td>
      <td><a href="https://arxiv.org/abs/1310.4546" target="_blank">arxiv</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>GraRep: Learning Graph Representations with Global Structural Information</td>
      <td>Cao et al</td>
      <td>2015</td>
      <td><a href="https://paperswithcode.com/paper/grarep-learning-graph-representations-with" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Noise-Contrastive Estimation of Unnormalized Statistical Models, with Applications to Natural Image Statistics</td>
      <td>Gutmann and Hyvärinen</td>
      <td>2012</td>
      <td><a href="https://jmlr.org/papers/v13/gutmann12a.html" target="_blank">リンク</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec</td>
      <td>Qiu et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1710.02971" target="_blank">arxiv</a></td>
      <td>9</td>
    </tr>
    <tr>
      <td>struc2vec: Learning Node Representations from Structural Identity</td>
      <td>Ribeiro et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1704.03165" target="_blank">arxiv</a></td>
      <td>10</td>
    </tr>
    <tr>
      <td>Structural equivalence: Meaning and definition, computation and application</td>
      <td>Sailer</td>
      <td>1978</td>
      <td><a href="https://www.sciencedirect.com/science/article/abs/pii/037887337890014X?via%3Dihub" target="_blank">リンク</a></td>
      <td>11</td>
    </tr>
    <tr>
      <td>FastDTW: Toward Accurate Dynamic Time Warping in Linear Time and Space</td>
      <td>Salvador and Chan</td>
      <td>2007</td>
      <td><a href="https://cs.fit.edu/~pkc/papers/tdm04.pdf" target="_blank">PDF</a></td>
      <td>12</td>
    </tr>
    <tr>
      <td>Preserving Local and Global Information for Network Embedding</td>
      <td>Ma et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1710.07266" target="_blank">arxiv</a></td>
      <td>13</td>
    </tr>
    <tr>
      <td>Modularity and community structure in networks</td>
      <td>Newman</td>
      <td>2006</td>
      <td><a href="https://arxiv.org/abs/physics/0602124" target="_blank">arxiv</a></td>
      <td>14</td>
    </tr>
    <tr>
      <td>Community Preserving Network Embedding</td>
      <td>Wang et al</td>
      <td>2017c</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/10488" target="_blank">リンク</a></td>
      <td>15</td>
    </tr>
    <tr>
      <td>Community Detection in Attributed Graphs: An Embedding Approach</td>
      <td>Li et al</td>
      <td>2018d</td>
      <td><a href="https://dl.acm.org/doi/10.5555/3504035.3504077" target="_blank">リンク</a></td>
      <td>16</td>
    </tr>
  </tbody>
</table>
<h3>4.3節 複雑グラフ上のグラフ埋め込み</h3>
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
      <td>Heterogeneous Network Embedding via Deep Architectures</td>
      <td>Chang et al</td>
      <td>2015</td>
      <td><a href="https://www.researchgate.net/publication/299970490_Heterogeneous_Network_Embedding_via_Deep_Architectures" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>metapath2vec: Scalable Representation Learning for Heterogeneous Networks</td>
      <td>Dong et al</td>
      <td>2017</td>
      <td><a href="https://paperswithcode.com/paper/metapath2vec-scalable-representation-learning" target="_blank">リンク</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>BiNE: Bipartite Network Embedding</td>
      <td>Gao et al</td>
      <td>2018b</td>
      <td><a href="https://staff.ustc.edu.cn/~hexn/papers/sigir18-bipartiteNE.pdf" target="_blank">PDF</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Multi-Dimensional Network Embedding with Hierarchical Structure</td>
      <td>Ma et al</td>
      <td>2018d</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3159652.3159680" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Signed Network Embedding in Social Media</td>
      <td>Wang et al</td>
      <td>2017b</td>
      <td><a href="https://epubs.siam.org/doi/10.1137/1.9781611974973.37" target="_blank">リンク</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>Sitting closer to friends than enemies, revisited</td>
      <td>Cygan et al</td>
      <td>2012</td>
      <td><a href="https://arxiv.org/abs/1201.1869" target="_blank">arxiv</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Is Distrust the Negation of Trust? The Value of Distrust in Social Media</td>
      <td>Tang et al</td>
      <td>2014b</td>
      <td><a href="https://www.semanticscholar.org/paper/Is-distrust-the-negation-of-trust%3A-the-value-of-in-Tang-Hu/bdde4a7c07d6fec4516d545c6629749c1b2a088f" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Structural Deep Embedding for Hyper-Networks</td>
      <td>Tu et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1711.10146" target="_blank">arxiv</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>Continuous-Time Dynamic Network Embeddings</td>
      <td>Nguyen et al</td>
      <td>2018</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3184558.3191526" target="_blank">リンク</a></td>
      <td>9</td>
    </tr>
  </tbody>
</table>
<h3>4.5節 参考文献</h3>
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
      <td>HONE: Higher-Order Network Embeddings</td>
      <td>Rossi et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1801.09303" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Asymmetric Transitivity Preserving Graph Embedding</td>
      <td>Ou et al</td>
      <td>2016</td>
      <td><a href="https://www.kdd.org/kdd2016/papers/files/rfp0184-ouA.pdf" target="_blank">PDF</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Learning social network embeddings for predicting information diffusion</td>
      <td>Bourigault et al</td>
      <td>2014</td>
      <td><a href="https://www.researchgate.net/publication/260433722_Learning_social_network_embeddings_for_predicting_information_diffusion" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Task-Guided and Path-Augmented Heterogeneous Network Embedding for Author Identification</td>
      <td>Chen and Sun</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1612.02814" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Heterogeneous Information Network Embedding for Recommendation</td>
      <td>Shi et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1711.10730" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>ActiveHNE: Active Heterogeneous Network Embedding</td>
      <td>Chen et al</td>
      <td>2019b</td>
      <td><a href="https://arxiv.org/abs/1905.05659" target="_blank">arxiv</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Bipartite Network Embedding via Effective Integration of Explicit and Implicit Relations</td>
      <td>Wang et al</td>
      <td>2019j</td>
      <td><a href="https://link.springer.com/chapter/10.1007/978-3-030-18576-3_26" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Cascade-BGNN: Toward Efficient Self-supervised Representation Learning on Large-scale Bipartite Graphs</td>
      <td>He et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1906.11994" target="_blank">arxiv</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>mvn2vec: Preservation and Collaboration in Multi-View Network Embedding</td>
      <td>Shi et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1801.06597" target="_blank">arxiv</a></td>
      <td>9</td>
    </tr>
    <tr>
      <td>SNE: Signed Network Embedding</td>
      <td>Yuan et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1703.04837" target="_blank">arxiv</a></td>
      <td>10</td>
    </tr>
    <tr>
      <td>Attributed Signed Network Embedding</td>
      <td>Wang et al</td>
      <td>2017a</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3132847.3132905" target="_blank">リンク</a></td>
      <td>11</td>
    </tr>
    <tr>
      <td>Heterogeneous Hyper-Network Embedding</td>
      <td>Baytas et al</td>
      <td>2018</td>
      <td><a href="https://par.nsf.gov/servlets/purl/10098519" target="_blank">リンク</a></td>
      <td>12</td>
    </tr>
    <tr>
      <td>Attributed Network Embedding for Learning in a Dynamic Environment</td>
      <td>Li et al</td>
      <td>2017a</td>
      <td><a href="https://arxiv.org/abs/1706.01860" target="_blank">arxiv</a></td>
      <td>13</td>
    </tr>
    <tr>
      <td>Dynamic Network Embedding by Modeling Triadic Closure Process</td>
      <td>Zhou et al</td>
      <td>2018b</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/11257" target="_blank">リンク</a></td>
      <td>14</td>
    </tr>
    <tr>
      <td>Representation Learning on Graphs: Methods and Applications</td>
      <td>Hamilton et al</td>
      <td>2017b</td>
      <td><a href="https://arxiv.org/abs/1709.05584" target="_blank">arxiv</a></td>
      <td>15</td>
    </tr>
    <tr>
      <td>Graph Embedding Techniques, Applications, and Performance: A Survey</td>
      <td>Goyal and Ferrara</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1705.02801" target="_blank">arxiv</a></td>
      <td>16</td>
    </tr>
    <tr>
      <td>A Comprehensive Survey of Graph Embedding: Problems, Techniques and Applications</td>
      <td>Cai et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1709.07604" target="_blank">arxiv</a></td>
      <td>17</td>
    </tr>
    <tr>
      <td>A Survey on Network Embedding</td>
      <td>Cui et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1711.08752" target="_blank">arxiv</a></td>
      <td>18</td>
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