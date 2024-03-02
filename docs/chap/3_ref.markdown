
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
    /* 1番目の列の幅を65%に設定 */
    table.display td:nth-child(1),
    table.display th:nth-child(1) {
        width: 65%;
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

<h3>3.1節 はじめに</h3>
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
      <td>A Logical Calculus of the Ideas Immanent in Nervous Activity</td>
      <td>McCulloch and Pitts</td>
      <td>1943</td>
      <td><a href="https://home.csulb.edu/~cwallis/382/readings/482/mccolloch.logical.calculus.ideas.1943.pdf" target="_blank">PDF</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>The perceptron: A probabilistic model for information storage and organization in the brain</td>
      <td>Rosenblatt</td>
      <td>1958</td>
      <td><a href="https://134.208.26.59/INA/A%20probabilistic%20model.pdf" target="_blank">PDF</a><br><a href="https://pdfs.semanticscholar.org/865f/b2cfe6fdb7af2c663ef346ea05889f237108.pdf" target="_blank">PDF</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Learning representations by back-propagating errors</td>
      <td>Rumelhart et al</td>
      <td>1986</td>
      <td><a href="https://www.semanticscholar.org/paper/Learning-representations-by-back-propagating-errors-Rumelhart-Hinton/052b1d8ce63b07fec3de9dbb583772d860b7c769" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Modèles connexionnistes de l'apprentissage</td>
      <td>Le Cun and Fogelman-Soulié</td>
      <td>1987</td>
      <td><a href="https://www.persee.fr/doc/intel_0769-4113_1987_num_2_1_1804" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>The Roots of Backpropagation: From Ordered Derivatives to Neural Networks and Political Forecasting</td>
      <td>Werbos</td>
      <td>1994</td>
      <td><a href="https://www.amazon.co.jp/dp/0471598976" target="_blank">amazon</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>ImageNet Classification with Deep Convolutional Neural Networks</td>
      <td>Krizhevsky et al</td>
      <td>2012</td>
      <td><a href="https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html" target="_blank">リンク</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Deep Residual Learning for Image Recognition</td>
      <td>He et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1512.03385" target="_blank">arxiv</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Phone Recognition with the Mean-Covariance Restricted Boltzmann Machine</td>
      <td>Dahl et al</td>
      <td>2010</td>
      <td><a href="https://papers.nips.cc/paper_files/paper/2010/hash/b73ce398c39f506af761d2277d853a92-Abstract.html" target="_blank">リンク</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>Binary Coding of Speech Spectrograms Using a Deep Auto-encoder</td>
      <td>Deng et al</td>
      <td>2010</td>
      <td><a href="https://www.microsoft.com/en-us/research/publication/binary-coding-of-speech-spectrograms-using-a-deep-auto-encoder/" target="_blank">リンク</a></td>
      <td>9</td>
    </tr>
    <tr>
      <td>Conversational Speech Transcription Using Context-Dependent Deep Neural Networks</td>
      <td>Seide et al</td>
      <td>2011</td>
      <td><a href="https://www.isca-archive.org/interspeech_2011/seide11_interspeech.html" target="_blank">リンク</a></td>
      <td>10</td>
    </tr>
    <tr>
      <td>Long Short-Term Memory</td>
      <td>Hochreiter and Schmidhuber</td>
      <td>1997</td>
      <td><a href="https://www.bioinf.jku.at/publications/older/2604.pdf" target="_blank">PDF</a></td>
      <td>11</td>
    </tr>
    <tr>
      <td>Sequence to Sequence Learning with Neural Networks</td>
      <td>Sutskever et al</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1409.3215" target="_blank">arxiv</a></td>
      <td>12</td>
    </tr>
    <tr>
      <td>Neural Machine Translation by Jointly Learning to Align and Translate</td>
      <td>Bahdanau et al</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1409.0473" target="_blank">arxiv</a></td>
      <td>13</td>
    </tr>
    <tr>
      <td>A Neural Conversational Model</td>
      <td>Vinyals and Le</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1506.05869" target="_blank">arxiv</a></td>
      <td>14</td>
    </tr>
    <tr>
      <td>Attention Is All You Need</td>
      <td>Vaswani et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1706.03762" target="_blank">arxiv</a></td>
      <td>15</td>
    </tr>
    <tr>
      <td>Improving Language Understanding by Generative Pre-Training</td>
      <td>Radford et al</td>
      <td>2018</td>
      <td><a href="https://paperswithcode.com/paper/improving-language-understanding-by" target="_blank">リンク</a></td>
      <td>16</td>
    </tr>
  </tbody>
</table>
<h3>3.2節 深層順伝播型ネットワーク</h3>
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
      <td>Rectifier nonlinearities improve neural network acoustic models</td>
      <td>Maas et al</td>
      <td>2013</td>
      <td><a href="https://www.stateoftheart.ai/papers/73d06dc5-1953-41bb-be13-71102341b93e" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Activation Functions: Comparison of trends in Practice and Research for Deep Learning</td>
      <td>Nwankpa et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1811.03378" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<h3>3.3節 畳み込みニューラルネットワーク</h3>
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
      <td>Convolution Transform</td>
      <td>Widder and Hirschman</td>
      <td>2015</td>
      <td><a href="https://www.amazon.co.jp/dp/0691626928" target="_blank">amazon</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>ImageNet Classification with Deep Convolutional Neural Networks</td>
      <td>Krizhevsky et al</td>
      <td>2012</td>
      <td><a href="https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html" target="_blank">リンク</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Deep Residual Learning for Image Recognition</td>
      <td>He et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1512.03385" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
  </tbody>
</table>
<h3>3.4節 RNN：リカレントニューラルネットワーク</h3>
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
      <td>Long Short-Term Memory</td>
      <td>Hochreiter and Schmidhuber</td>
      <td>1997</td>
      <td><a href="https://www.bioinf.jku.at/publications/older/2604.pdf" target="_blank">PDF</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation</td>
      <td>Cho et al</td>
      <td>2014a</td>
      <td><a href="https://arxiv.org/abs/1406.1078" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<h3>3.5節 オートエンコーダー（自己符号化器）</h3>
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
      <td>Sparse coding with an overcomplete basis set: A strategy employed by V1?</td>
      <td>Olshausen and Field</td>
      <td>1997</td>
      <td><a href="https://www.sciencedirect.com/science/article/pii/S0042698997001697" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Sparse autoencoder</td>
      <td>Ng et al</td>
      <td>2011</td>
      <td><a href="https://web.stanford.edu/class/cs294a/sparseAutoencoder_2011new.pdf" target="_blank">PDF</a></td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<h3>3.6節 深層ニューラルネットワークの学習</h3>
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
      <td>Adaptive Subgradient Methods for Online Learning and Stochastic Optimization</td>
      <td>Duchi et al</td>
      <td>2011</td>
      <td><a href="https://jmlr.org/papers/v12/duchi11a.html" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>ADADELTA: An Adaptive Learning Rate Method</td>
      <td>Zeiler</td>
      <td>2012</td>
      <td><a href="https://arxiv.org/abs/1212.5701" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Adam: A Method for Stochastic Optimization</td>
      <td>Kingma and Ba</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1412.6980" target="_blank">arxiv</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Dropout: A Simple Way to Prevent Neural Networks from Overfitting</td>
      <td>Srivastava et al</td>
      <td>2014</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.5555/2627435.2670313" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift</td>
      <td>Ioffe and Szegedy</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1502.03167" target="_blank">arxiv</a></td>
      <td>5</td>
    </tr>
  </tbody>
</table>
<h3>3.8節 参考文献</h3>
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
      <td>Linear Algebra</td>
      <td>Hoffman and Kunze</td>
      <td>2015</td>
      <td><a href="https://www.amazon.co.jp/dp/9332550077" target="_blank">amazon</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>An Introduction to Probability Theory and Its Applications</td>
      <td>Feller</td>
      <td>1957</td>
      <td><a href="https://www.amazon.co.jp/dp/0471257087" target="_blank">amazon</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Convex Optimization</td>
      <td>Boyd et al</td>
      <td>2004</td>
      <td><a href="https://web.stanford.edu/~boyd/cvxbook/" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Linear Algebra and Optimization for Machine Learning</td>
      <td>Aggarwal</td>
      <td>2020</td>
      <td><a href="https://www.amazon.co.jp/dp/3030403432" target="_blank">amazon</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Pattern Recognition and Machine Learning</td>
      <td>Bishop</td>
      <td>2006</td>
      <td><a href="https://www.amazon.co.jp/dp/0387310738" target="_blank">amazon</a><br><a href="https://www.amazon.co.jp/dp/4621061224" target="_blank">amazon</a><br><a href="https://www.amazon.co.jp/dp/4621061240" target="_blank">amazon</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>Deep Learning</td>
      <td>Goodfellow et al</td>
      <td>2016</td>
      <td><a href="https://www.amazon.co.jp/dp/0262035618" target="_blank">amazon</a><br><a href="https://www.amazon.co.jp/dp/4048930621" target="_blank">amazon</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Neural Networks and Deep Learning</td>
      <td>Aggarwal</td>
      <td>2023</td>
      <td><a href="https://www.amazon.co.jp/dp/3031296419" target="_blank">amazon</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems</td>
      <td>Abadi et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1603.04467" target="_blank">arxiv</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>PyTorch: An Imperative Style, High-Performance Deep Learning Library</td>
      <td>Paszke et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1912.01703" target="_blank">arxiv</a></td>
      <td>9</td>
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