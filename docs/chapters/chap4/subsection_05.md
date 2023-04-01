[メインページ](../../index.markdown)

[章目次](./chap4.md)
## 4.5. 参考文献

これまで述べてこなかったような情報を保存する埋め込みアルゴリズムも存在する．
Rossi et
al.(2018)では，モチーフ(motifs)を抽出し，そのノード表現を保存している．
有向グラフに対しては，非対称な推移情報を保存するネットワーク埋め込みアルゴリズムがOu
et al.(2016)で提案されている．Bourigault et
al.(2014)では，情報拡散(information
diffusion)をモデル化し予測するためのノード表現を学習している．
複合グラフについては，代表的なアルゴリズムのみを紹介してきたが，複合グラフの種類に応じて，より多くのアルゴリズムが存在している．
例えば次を参照されたい：Heterogeneousグラフ(Chen and Sun, 2017; Shi et
al., 2018a; Chen et al., 2019b)，二部グラフ(Wang et al., 2019j; He et
al., 2019)，多次元グラフ(Shi et al., 2018b)，符号付きグラフ(Yuan et al.,
2017; Wang et al., 2017a)，ハイパーグラフ(Baytas et al.,
2018)，ダイナミックグラフ(Li et al., 2017a; Zhou et al., 2018b)．
また，グラフエンベディングに関するサーベイも数多く行われている(Hamilton
et al., 2017b; Goyal and Ferrara, 2018; Cai et al., 2018; Cui et al.,
2018)．

[^1]: 訳注：本書では状況によって「エンベディング」と「埋め込み」を使い分けているが，いずれもEmbeddingの訳語である．

[^2]: 訳注：入力されたキー(Key)に対して出力値(Value)を割り当てるデータ表現

[^3]: 訳注：木構造(tree
    structure)とは，根(root)と呼ばれるトップのノードから始まり，葉(leaf)と呼ばれる最下層のノードで終わる，階層を持ったデータ構造である．その中でも，二分木(binary
    tree)は最大で2つの子ノードを持つ木構造である．

[^4]: 訳注：未知の確率密度分布をモデル化する際，正規化定数(定義域に渡る積分)を扱うことは計算上困難を極める．そこで，NCEでは，「正規化定数もパラメータとして導入し，観測データと人工的に作ったノイズ(noise)を対照的(contrastive)識別する2値分類問題」を考えることでこの問題を回避している．

[^5]: 訳注： $d(v)$ はノード $v$ の次数を表す．すなわち，ノイズ分布は次数の大きさに比例したノードを負例としてサンプリングすることになる． $3/4$ 乗することはあくまで一つの手法であり，必ずしも必要ではない． $3/4$ 乗が有効な理由は，確率分布の重みを微調整することにより，次数が大きいノードに対してはやや低い確率でサンプリングし，次数が小さいノードに対してはやや高い確率でサンプリングすることができるためである．これにより，よりバランスの取れたサンプリングが実現できるとされている．

[^6]: 訳注：LINEでは，ノード間の直接的な繋がりを意味した"第一次近接性"(first-order
    proximity)と，間接的な繋がりを意味した"第二次近接性"(second-order
    proximity)が定義され，これらの近接性を保持するように学習する．本議論では第二次近接性に関する目的関数を扱っているが，第一次近接性についても類似した形の目的関数が使われる．

[^7]: 訳注：次数列(degree
    sequence)とは，グラフ中の全ノードの次数を集めてそれらを降順（または昇順）に並べた数列である．本文では $k$ 次近傍のノードだけを対象にした次数列を構成していることに注意．

[^8]: 訳注：多層的重み付きグラフ(multilayer weighted
    graph)は，直感的には複数のグラフ $\symbfscr{G}$ を（層を成すように）積み上げ，それら層の間にエッジを結ぶことで構成されるグラフである．

[^9]: 訳注：任意のノード組に対して構造距離 $g\_k(\cdot,\cdot)$ が計算できるので， $k^{\ast}$ 層グラフは，完全グラフ(complete
    graph)を $k^{\ast}$ 個積み重ねたグラフとみなせる．

[^10]: 訳注： $v_{(i)}$ の方が $v_{(j)}$ よりランクが高く，大きい大域的な状態スコアを持つ確率．

[^11]: 訳注：複数種類のノード「A:著者，P:論文，V:学会」を含んだグラフを考える．このとき，「共著関係」の意味を持つ関係は"APA"，「同じ学会に論文を提出した著者関係」の意味を持つ関係は"APVPA"と表すことができる．このような特定の経路に生じる関係を"意味的な相互関係"と呼び，"構造的な相互関係"と区別している．

[^12]: 訳注：マッピング関数とは別の学習パラメータを持つことになる．

[メインページ](../../index.markdown)

[章目次](./chap4.md)