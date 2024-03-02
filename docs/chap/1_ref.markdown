
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

<h3>1.2節 なぜグラフニューラルネットワークなのか？</h3>
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
      <td>Representing Big Data as Networks: New Methods and Insights</td>
      <td>Xu</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1712.09648" target="_blank">arxiv</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Node Classification in Social Networks</td>
      <td>Bhagat et al</td>
      <td>2011</td>
      <td><a href="https://arxiv.org/abs/1101.3291" target="_blank">arxiv</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>The Link-Prediction Problem for Social Networks</td>
      <td>Liben-Nowell and Kleinberg</td>
      <td>2007</td>
      <td><a href="https://cs.carleton.edu/faculty/dlibenno/papers/link-prediction/link.pdf" target="_blank">PDF</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Collective Classification in Network Data</td>
      <td>Sen et al</td>
      <td>2008</td>
      <td><a href="https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/2157" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
  </tbody>
</table>
<h3>1.5節 グラフの表現学習に関する歴史</h3>
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
      <td>Towards Feature Selection in Networks</td>
      <td>Gu and Han</td>
      <td>2011</td>
      <td><a href="https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=1d9e493a34df3fc2d7eec5b343ea91f9fc474678" target="_blank">リンク</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Feature Selection with Linked Data in Social Media</td>
      <td>Tang and Liu</td>
      <td>2012a</td>
      <td><a href="https://epubs.siam.org/doi/10.1137/1.9781611972825.11" target="_blank">リンク</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Efficient Partial Order Preserving Unsupervised Feature Selection on Networks</td>
      <td>Wei et al</td>
      <td>2015</td>
      <td><a href="https://epubs.siam.org/doi/10.1137/1.9781611974010.10" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Unsupervised Feature Selection on Networks: A Generative View</td>
      <td>Wei et al</td>
      <td>2016</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/10309" target="_blank">リンク</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Unsupervised Feature Selection for Linked Social Media Data</td>
      <td>Tang and Liu</td>
      <td>2012b</td>
      <td><a href="https://www.semanticscholar.org/paper/Unsupervised-feature-selection-for-linked-social-Tang-Liu/ec8c47ef5797976594c7b784dcad6776743ef014" target="_blank">リンク</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>Toward Time-Evolving Feature Selection on Dynamic Networks</td>
      <td>Li et al</td>
      <td>2016</td>
      <td><a href="https://www.semanticscholar.org/paper/Toward-Time-Evolving-Feature-Selection-on-Dynamic-Li-Hu/f831be455cba1db826715e3caf7957fae1e5169d" target="_blank">リンク</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Unsupervised Feature Selection for Multi-View Data in Social Media</td>
      <td>Tang et al</td>
      <td>2013b</td>
      <td><a href="https://www.semanticscholar.org/paper/Unsupervised-Feature-Selection-for-Multi-View-Data-Tang-Hu/27e2af1d9775974485ff0b642aec57326a791411" target="_blank">リンク</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Unsupervised Feature Selection in Signed Social Networks</td>
      <td>Cheng et al</td>
      <td>2017</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3097983.3098106" target="_blank">リンク</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>Unsupervised Nonlinear Feature Selection from High-Dimensional Signed Networks</td>
      <td>Huang et al</td>
      <td>2020</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/5839" target="_blank">リンク</a></td>
      <td>9</td>
    </tr>
    <tr>
      <td>Adaptive Unsupervised Feature Selection on Attributed Networks</td>
      <td>Li et al</td>
      <td>2019b</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3292500.3330856" target="_blank">リンク</a></td>
      <td>10</td>
    </tr>
    <tr>
      <td>Normalized Cuts and Image Segmentation</td>
      <td>Shi and Malik</td>
      <td>2000</td>
      <td><a href="https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf" target="_blank">PDF</a></td>
      <td>11</td>
    </tr>
    <tr>
      <td>On Spectral Clustering: Analysis and an algorithm</td>
      <td>Ng et al</td>
      <td>2002</td>
      <td><a href="https://papers.nips.cc/paper_files/paper/2001/hash/801272ee79cfde7fa5960571fee36b9b-Abstract.html" target="_blank">リンク</a></td>
      <td>12</td>
    </tr>
    <tr>
      <td>Laplacian Eigenmaps for Dimensionality Reduction and Data Representation</td>
      <td>Belkin and Niyogi</td>
      <td>2003</td>
      <td><a href="https://www2.imm.dtu.dk/projects/manifold/Papers/Laplacian.pdf" target="_blank">PDF</a></td>
      <td>13</td>
    </tr>
    <tr>
      <td>A Global Geometric Framework for Nonlinear Dimensionality Reduction</td>
      <td>Tenenbaum et al</td>
      <td>2000</td>
      <td><a href="https://www.robots.ox.ac.uk/~az/lectures/ml/tenenbaum-isomap-Science2000.pdf" target="_blank">PDF</a></td>
      <td>14</td>
    </tr>
    <tr>
      <td>Nonlinear Dimensionality Reduction by Locally Linear Embedding</td>
      <td>Roweis and Saul</td>
      <td>2000</td>
      <td><a href="https://www.robots.ox.ac.uk/~az/lectures/ml/lle.pdf" target="_blank">PDF</a></td>
      <td>15</td>
    </tr>
    <tr>
      <td>Combining Content and Link for Classification using Matrix Factorization</td>
      <td>Zhu et al</td>
      <td>2007</td>
      <td><a href="https://www.dbs.ifi.lmu.de/~yu_k/sigir2007_mf.pdf" target="_blank">PDF</a></td>
      <td>16</td>
    </tr>
    <tr>
      <td>Exploiting Homophily Effect for Trust Prediction</td>
      <td>Tang et al</td>
      <td>2013a</td>
      <td><a href="https://www.semanticscholar.org/paper/Exploiting-homophily-effect-for-trust-prediction-Tang-Gao/04b3e9e7abe8b2d0be8ddfe080750bc4cb9473d9" target="_blank">リンク</a></td>
      <td>17</td>
    </tr>
    <tr>
      <td>Matrix Factorization Techniques for Recommender Systems</td>
      <td>Koren et al</td>
      <td>2009</td>
      <td><a href="https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf" target="_blank">PDF</a></td>
      <td>18</td>
    </tr>
    <tr>
      <td>Indexing by Latent Semantic Analysis</td>
      <td>Deerwester et al</td>
      <td>1990</td>
      <td><a href="https://wordvec.colorado.edu/papers/Deerwester_1990.pdf" target="_blank">PDF</a></td>
      <td>19</td>
    </tr>
    <tr>
      <td>Node Classification in Signed Social Networks</td>
      <td>Tang et al</td>
      <td>2016a</td>
      <td><a href="https://www.semanticscholar.org/paper/Node-Classification-in-Signed-Social-Networks-Tang-Aggarwal/41a08affbb5c847d6f2a82d5ae4be9ed5df52353" target="_blank">リンク</a></td>
      <td>20</td>
    </tr>
    <tr>
      <td>Link Prediction via Matrix Factorization</td>
      <td>Menon and Elkan</td>
      <td>2011</td>
      <td><a href="https://link.springer.com/chapter/10.1007/978-3-642-23783-6_28#preview" target="_blank">リンク</a></td>
      <td>21</td>
    </tr>
    <tr>
      <td>Community discovery using nonnegative matrix factorization</td>
      <td>Wang et al</td>
      <td>2011</td>
      <td><a href="https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=df89be8356e1f2c6bd2269ef6fb1bc326c149e50" target="_blank">リンク</a></td>
      <td>22</td>
    </tr>
    <tr>
      <td>Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec</td>
      <td>Qiu et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1710.02971" target="_blank">arxiv</a></td>
      <td>23</td>
    </tr>
    <tr>
      <td>Distributed Representations of Words and Phrases and their Compositionality</td>
      <td>Mikolov et al</td>
      <td>2013</td>
      <td><a href="https://arxiv.org/abs/1310.4546" target="_blank">arxiv</a></td>
      <td>24</td>
    </tr>
    <tr>
      <td>DeepWalk: Online Learning of Social Representations</td>
      <td>Perozzi et al</td>
      <td>2014</td>
      <td><a href="https://arxiv.org/abs/1403.6652" target="_blank">arxiv</a></td>
      <td>25</td>
    </tr>
    <tr>
      <td>LINE: Large-scale Information Network Embedding</td>
      <td>Tang et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1503.03578" target="_blank">arxiv</a></td>
      <td>26</td>
    </tr>
    <tr>
      <td>node2vec: Scalable Feature Learning for Networks</td>
      <td>Grover and Leskovec</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1607.00653" target="_blank">arxiv</a></td>
      <td>27</td>
    </tr>
    <tr>
      <td>GraRep: Learning Graph Representations with Global Structural Information</td>
      <td>Cao et al</td>
      <td>2015</td>
      <td><a href="https://paperswithcode.com/paper/grarep-learning-graph-representations-with" target="_blank">リンク</a></td>
      <td>28</td>
    </tr>
    <tr>
      <td>struc2vec: Learning Node Representations from Structural Identity</td>
      <td>Ribeiro et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1704.03165" target="_blank">arxiv</a></td>
      <td>29</td>
    </tr>
    <tr>
      <td>Community Preserving Network Embedding</td>
      <td>Wang et al</td>
      <td>2017c</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/10488" target="_blank">リンク</a></td>
      <td>30</td>
    </tr>
    <tr>
      <td>Preserving Local and Global Information for Network Embedding</td>
      <td>Ma et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1710.07266" target="_blank">arxiv</a></td>
      <td>31</td>
    </tr>
    <tr>
      <td>PRUNE: Preserving Proximity and Global Ranking for Network Embedding</td>
      <td>Lai et al</td>
      <td>2017</td>
      <td><a href="https://proceedings.neurips.cc/paper/2017/hash/cdd96eedd7f695f4d61802f8105ba2b0-Abstract.html" target="_blank">リンク</a></td>
      <td>32</td>
    </tr>
    <tr>
      <td>RaRE: Social Rank Regulated Large-scale Network Embedding</td>
      <td>Gu et al</td>
      <td>2018</td>
      <td><a href="https://dl.acm.org/doi/abs/10.1145/3178876.3186102" target="_blank">リンク</a></td>
      <td>33</td>
    </tr>
    <tr>
      <td>Asymmetric Transitivity Preserving Graph Embedding</td>
      <td>Ou et al</td>
      <td>2016</td>
      <td><a href="https://www.kdd.org/kdd2016/papers/files/rfp0184-ouA.pdf" target="_blank">PDF</a></td>
      <td>34</td>
    </tr>
    <tr>
      <td>Heterogeneous Network Embedding via Deep Architectures</td>
      <td>Chang et al</td>
      <td>2015</td>
      <td><a href="https://www.researchgate.net/publication/299970490_Heterogeneous_Network_Embedding_via_Deep_Architectures" target="_blank">リンク</a></td>
      <td>35</td>
    </tr>
    <tr>
      <td>metapath2vec: Scalable Representation Learning for Heterogeneous Networks</td>
      <td>Dong et al</td>
      <td>2017</td>
      <td><a href="https://paperswithcode.com/paper/metapath2vec-scalable-representation-learning" target="_blank">リンク</a></td>
      <td>36</td>
    </tr>
    <tr>
      <td>BiNE: Bipartite Network Embedding</td>
      <td>Gao et al</td>
      <td>2018b</td>
      <td><a href="https://staff.ustc.edu.cn/~hexn/papers/sigir18-bipartiteNE.pdf" target="_blank">PDF</a></td>
      <td>37</td>
    </tr>
    <tr>
      <td>Multi-Dimensional Network Embedding with Hierarchical Structure</td>
      <td>Ma et al</td>
      <td>2018d</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3159652.3159680" target="_blank">リンク</a></td>
      <td>38</td>
    </tr>
    <tr>
      <td>Signed Network Embedding in Social Media</td>
      <td>Wang et al</td>
      <td>2017b</td>
      <td><a href="https://epubs.siam.org/doi/10.1137/1.9781611974973.37" target="_blank">リンク</a></td>
      <td>39</td>
    </tr>
    <tr>
      <td>Structural Deep Embedding for Hyper-Networks</td>
      <td>Tu et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1711.10146" target="_blank">arxiv</a></td>
      <td>40</td>
    </tr>
    <tr>
      <td>Continuous-Time Dynamic Network Embeddings</td>
      <td>Nguyen et al</td>
      <td>2018</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3184558.3191526" target="_blank">リンク</a></td>
      <td>41</td>
    </tr>
    <tr>
      <td>Attributed Network Embedding for Learning in a Dynamic Environment</td>
      <td>Li et al</td>
      <td>2017a</td>
      <td><a href="https://arxiv.org/abs/1706.01860" target="_blank">arxiv</a></td>
      <td>42</td>
    </tr>
    <tr>
      <td>Graph neural networks for ranking Web pages</td>
      <td>Scarselli et al</td>
      <td>2005</td>
      <td><a href="https://www.semanticscholar.org/paper/Graph-neural-networks-for-ranking-Web-pages-Scarselli-Yong/769bfd4a4b45979cf83bb56c054ebcaaaf8b35d7" target="_blank">リンク</a></td>
      <td>43</td>
    </tr>
    <tr>
      <td>Spectral Networks and Locally Connected Networks on Graphs</td>
      <td>Bruna et al</td>
      <td>2013</td>
      <td><a href="https://arxiv.org/abs/1312.6203" target="_blank">arxiv</a></td>
      <td>44</td>
    </tr>
    <tr>
      <td>Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering</td>
      <td>Defferrard et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1606.09375" target="_blank">arxiv</a></td>
      <td>45</td>
    </tr>
    <tr>
      <td>Semi-Supervised Classification with Graph Convolutional Networks</td>
      <td>Kipf and Welling</td>
      <td>2016a</td>
      <td><a href="https://arxiv.org/abs/1609.02907" target="_blank">arxiv</a></td>
      <td>46</td>
    </tr>
    <tr>
      <td>Diffusion-Convolutional Neural Networks</td>
      <td>Atwood and Towsley</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1511.02136" target="_blank">arxiv</a></td>
      <td>47</td>
    </tr>
    <tr>
      <td>Learning Convolutional Neural Networks for Graphs</td>
      <td>Niepert et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1605.05273" target="_blank">arxiv</a></td>
      <td>48</td>
    </tr>
    <tr>
      <td>Neural Message Passing for Quantum Chemistry</td>
      <td>Gilmer et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1704.01212" target="_blank">arxiv</a></td>
      <td>49</td>
    </tr>
    <tr>
      <td>Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks</td>
      <td>Monti et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1704.06803" target="_blank">arxiv</a></td>
      <td>50</td>
    </tr>
    <tr>
      <td>Graph Attention Networks</td>
      <td>Veličković et al</td>
      <td>2017</td>
      <td><a href="https://arxiv.org/abs/1710.10903" target="_blank">arxiv</a></td>
      <td>51</td>
    </tr>
    <tr>
      <td>Inductive Representation Learning on Large Graphs</td>
      <td>Hamilton et al</td>
      <td>2017a</td>
      <td><a href="https://arxiv.org/abs/1706.02216" target="_blank">arxiv</a></td>
      <td>52</td>
    </tr>
    <tr>
      <td>Gated Graph Sequence Neural Networks</td>
      <td>Li et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1511.05493" target="_blank">arxiv</a></td>
      <td>53</td>
    </tr>
    <tr>
      <td>Hierarchical Graph Representation Learning with Differentiable Pooling</td>
      <td>Ying et al</td>
      <td>2018c</td>
      <td><a href="https://arxiv.org/abs/1806.08804" target="_blank">arxiv</a></td>
      <td>54</td>
    </tr>
    <tr>
      <td>Graph U-Nets</td>
      <td>Gao and Ji</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1905.05178" target="_blank">arxiv</a></td>
      <td>55</td>
    </tr>
    <tr>
      <td>Graph Convolutional Networks with EigenPooling</td>
      <td>Ma et al</td>
      <td>2019b</td>
      <td><a href="https://arxiv.org/abs/1904.13107" target="_blank">arxiv</a></td>
      <td>56</td>
    </tr>
    <tr>
      <td>Adversarial Attacks on Neural Networks for Graph Data</td>
      <td>Zügner et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1805.07984" target="_blank">arxiv</a></td>
      <td>57</td>
    </tr>
    <tr>
      <td>Adversarial Attacks on Graph Neural Networks via Meta Learning</td>
      <td>Zügner and Günnemann</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1902.08412" target="_blank">arxiv</a></td>
      <td>58</td>
    </tr>
    <tr>
      <td>Adversarial Attack on Graph Structured Data</td>
      <td>Dai et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1806.02371" target="_blank">arxiv</a></td>
      <td>59</td>
    </tr>
    <tr>
      <td>Attacking Graph Convolutional Networks via Rewiring</td>
      <td>Ma et al</td>
      <td>2019d</td>
      <td><a href="https://arxiv.org/abs/1906.03750" target="_blank">arxiv</a></td>
      <td>60</td>
    </tr>
    <tr>
      <td>Robust Graph Convolutional Networks Against Adversarial Attacks</td>
      <td>Zhu et al</td>
      <td>2019a</td>
      <td><a href="https://pengcui.thumedialab.com/papers/RGCN.pdf" target="_blank">PDF</a></td>
      <td>61</td>
    </tr>
    <tr>
      <td>Transferring Robustness for Graph Neural Network Against Poisoning Attacks</td>
      <td>Tang et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1908.07558" target="_blank">arxiv</a></td>
      <td>62</td>
    </tr>
    <tr>
      <td>Graph Structure Learning for Robust Graph Neural Networks</td>
      <td>Jin et al</td>
      <td>2020b</td>
      <td><a href="https://arxiv.org/abs/2005.10203" target="_blank">arxiv</a></td>
      <td>63</td>
    </tr>
    <tr>
      <td>Stochastic Training of Graph Convolutional Networks with Variance Reduction</td>
      <td>Chen et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1710.10568" target="_blank">arxiv</a></td>
      <td>64</td>
    </tr>
    <tr>
      <td>FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling</td>
      <td>Chen et al</td>
      <td>2018b</td>
      <td><a href="https://arxiv.org/abs/1801.10247" target="_blank">arxiv</a></td>
      <td>65</td>
    </tr>
    <tr>
      <td>Adaptive Sampling Towards Fast Graph Representation Learning</td>
      <td>Huang et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1809.05343" target="_blank">arxiv</a></td>
      <td>66</td>
    </tr>
    <tr>
      <td>Deep Collective Classification in Heterogeneous Information Networks</td>
      <td>Zhang et al</td>
      <td>2018b</td>
      <td><a href="https://dl.acm.org/doi/10.1145/3178876.3186106" target="_blank">リンク</a></td>
      <td>67</td>
    </tr>
    <tr>
      <td>Heterogeneous Graph Attention Network</td>
      <td>Wang et al</td>
      <td>2019i</td>
      <td><a href="https://arxiv.org/abs/1903.07293" target="_blank">arxiv</a></td>
      <td>68</td>
    </tr>
    <tr>
      <td>ActiveHNE: Active Heterogeneous Network Embedding</td>
      <td>Chen et al</td>
      <td>2019b</td>
      <td><a href="https://arxiv.org/abs/1905.05659" target="_blank">arxiv</a></td>
      <td>69</td>
    </tr>
    <tr>
      <td>Cascade-BGNN: Toward Efficient Self-supervised Representation Learning on Large-scale Bipartite Graphs</td>
      <td>He et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1906.11994" target="_blank">arxiv</a></td>
      <td>70</td>
    </tr>
    <tr>
      <td>Multi-dimensional Graph Convolutional Networks</td>
      <td>Ma et al</td>
      <td>2019c</td>
      <td><a href="https://arxiv.org/abs/1808.06099" target="_blank">arxiv</a></td>
      <td>71</td>
    </tr>
    <tr>
      <td>Signed Graph Convolutional Network</td>
      <td>Derr et al</td>
      <td>2018</td>
      <td><a href="https://arxiv.org/abs/1808.06354" target="_blank">arxiv</a></td>
      <td>72</td>
    </tr>
    <tr>
      <td>Hypergraph Neural Networks</td>
      <td>Feng et al</td>
      <td>2019b</td>
      <td><a href="https://arxiv.org/abs/1809.09401" target="_blank">arxiv</a></td>
      <td>73</td>
    </tr>
    <tr>
      <td>HyperGCN: A New Method of Training Graph Convolutional Networks on Hypergraphs</td>
      <td>Yadati et al</td>
      <td>2019</td>
      <td><a href="https://dl.acm.org/doi/10.5555/3454287.3454422" target="_blank">リンク</a></td>
      <td>74</td>
    </tr>
    <tr>
      <td>EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs</td>
      <td>Pareja et al</td>
      <td>2019</td>
      <td><a href="https://arxiv.org/abs/1902.10191" target="_blank">arxiv</a></td>
      <td>75</td>
    </tr>
    <tr>
      <td>Structural Deep Network Embedding</td>
      <td>Wang et al</td>
      <td>2016</td>
      <td><a href="https://dl.acm.org/doi/10.1145/2939672.2939753" target="_blank">リンク</a></td>
      <td>76</td>
    </tr>
    <tr>
      <td>Deep Neural Networks for Learning Graph Representations</td>
      <td>Cao et al</td>
      <td>2016</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/10179" target="_blank">リンク</a></td>
      <td>77</td>
    </tr>
    <tr>
      <td>Variational Graph Auto-Encoders</td>
      <td>Kipf and Welling</td>
      <td>2016b</td>
      <td><a href="https://arxiv.org/abs/1611.07308" target="_blank">arxiv</a></td>
      <td>78</td>
    </tr>
    <tr>
      <td>Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks</td>
      <td>Tai et al</td>
      <td>2015</td>
      <td><a href="https://arxiv.org/abs/1503.00075" target="_blank">arxiv</a></td>
      <td>79</td>
    </tr>
    <tr>
      <td>Semantic Object Parsing with Graph LSTM</td>
      <td>Liang et al</td>
      <td>2016</td>
      <td><a href="https://arxiv.org/abs/1603.07063" target="_blank">arxiv</a></td>
      <td>80</td>
    </tr>
    <tr>
      <td>GraphGAN: Graph Representation Learning with Generative Adversarial Nets</td>
      <td>Wang et al</td>
      <td>2018a</td>
      <td><a href="https://arxiv.org/abs/1711.08267" target="_blank">arxiv</a></td>
      <td>81</td>
    </tr>
  </tbody>
</table>
<h3>1.7節 参考文献</h3>
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
      <td>Computational Methods of Feature Selection</td>
      <td>Liu and Motoda</td>
      <td>2007</td>
      <td><a href="https://www.amazon.co.jp/dp/1584888784" target="_blank">amazon</a></td>
      <td>1</td>
    </tr>
    <tr>
      <td>Feature Selection for Knowledge Discovery and Data Mining</td>
      <td>Liu and Motoda</td>
      <td>2012</td>
      <td><a href="https://www.amazon.com/dp/079238198X" target="_blank">amazon</a></td>
      <td>2</td>
    </tr>
    <tr>
      <td>Feature Selection for Classification: A Review</td>
      <td>Tang et al</td>
      <td>2014a</td>
      <td><a href="https://www.semanticscholar.org/paper/Feature-Selection-for-Classification%3A-A-Review-Tang-Alelyani/ce2fa0dbf76d20369f793c11d2d8803880a9ab2d" target="_blank">リンク</a></td>
      <td>3</td>
    </tr>
    <tr>
      <td>Feature Selection: A Data Perspective</td>
      <td>Li et al</td>
      <td>2017b</td>
      <td><a href="https://arxiv.org/abs/1601.07996" target="_blank">arxiv</a></td>
      <td>4</td>
    </tr>
    <tr>
      <td>Deep Learning</td>
      <td>Goodfellow et al</td>
      <td>2016</td>
      <td><a href="https://www.amazon.co.jp/dp/0262035618" target="_blank">amazon</a><br><a href="https://www.amazon.co.jp/dp/4048930621" target="_blank">amazon</a></td>
      <td>5</td>
    </tr>
    <tr>
      <td>Neural Networks and Deep Learning</td>
      <td>Aggarwal</td>
      <td>2023</td>
      <td><a href="https://www.amazon.co.jp/dp/3031296419" target="_blank">amazon</a></td>
      <td>6</td>
    </tr>
    <tr>
      <td>Automatic Speech Recognition: A Deep Learning Approach</td>
      <td>Yu and Deng</td>
      <td>2016</td>
      <td><a href="https://www.amazon.co.jp/dp/1447169670" target="_blank">amazon</a></td>
      <td>7</td>
    </tr>
    <tr>
      <td>Deep Learning for NLP and Speech Recognition</td>
      <td>Kamath et al</td>
      <td>2019</td>
      <td><a href="https://www.amazon.co.jp/dp/3030145956" target="_blank">amazon</a></td>
      <td>8</td>
    </tr>
    <tr>
      <td>Deep Learning in Natural Language Processing</td>
      <td>Deng and Liu</td>
      <td>2018</td>
      <td><a href="https://www.amazon.co.jp/dp/9811338485" target="_blank">amazon</a></td>
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