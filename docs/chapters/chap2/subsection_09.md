[メインページ](../../index.markdown)
[章目次](./chap2.md)
## 2.9. 参考文献

グラフに関する多くの基本的な概念を簡単に紹介してきたが，グラフには"フロー"や"カット"など，グラフに関するより高度な性質や概念も存在する．さらにグラフ上で定義される問題には，グラフ彩色問題や経路問題，ネットワークフロー問題，被覆問題などが数多く含まれている．これらの概念とトピックには「Graph
Theory with Applications (Bondy et al., n.d.)」「Networks (Newman,
2018)」という本で取り上げている．また，グラフ上のスペクトルに関するより詳細な性質や理論に関しては，「Spectral
Graph Theory (Chung and Graham, 1997)」に掲載されている．
グラフのさまざまな分野での応用に関しては，(Boragatti et al., 2009;
Nastase et al., 2015; Trinajstic, 2018)の文献で確認できる．「Stanford
Large Network Dataset Collection (Leskovec and Krevl, 2014)」や「Network
Data Repository (Rossi and Ahmed,
2015)」では，多岐にわたる分野のグラフのデータセットを大量に管理している．また，PythonライブラリであるNetworkX
(Hag-berg et al., 2008)や，Graph-tool (Peixoto, 2014)，SNAP (Leskovec
and Sosič,
2016)は，グラフデータの解析・可視化に用いることができる．グラフ信号処理を実施するには，「Graph
Signal Processing Toolbox (Perraudin et al., 2014)」を利用すると良い．

[^1]: 訳注：辺の向きがある有向グラフでは，どのノードからもエッジの入射がないノードの中心性は $0$ となる．さらに，そのようなノードに隣接するノードも，中心性が $0$ となってしまう可能性がある．Katz中心性は，中心性が $0$ となるノードから入射するエッジにも一定のスコアを与えることで，より妥当な中心性の算出を可能にする指標である．

[^2]: 訳注：式(2.5)の"条件数"(condition
    number)が大きくなると，数値解析上の問題が生じる．一般に，方程式 $\symbf{C}\symbf{x}=\symbf{b}$ の条件数 $\kappa(\symbf{C})$ とは， $\kappa(\symbf{C})=\|\symbf{C}\|\,\|\symbf{C}^{-1}\|$ で定義される値であり( $\|\cdot\|$ は適当な行列ノルム)，この値が大きいほど，数値的な不安定性や誤差が生じることがある．そのため，Katz中心性を計算する際には，条件数 $\kappa(\symbf{I}-\alpha\cdot\symbf{A})$ を小さくするため， $\alpha$ の値の決め方が重要となってくる．

[^3]: 訳注： $\symbf{u}^T_l \symbf{L}\symbf{u}_l$ は式(2.10)右辺の形に変形できるから，固有値（周波数）が大きければ，エッジで接続されたノードの固有ベクトルの要素は互いに大きく異なることになる．
