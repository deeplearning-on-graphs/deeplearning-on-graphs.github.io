[メインページ](../../index.markdown)

[章目次](./chap2.md)
## 2.6. 複合グラフ

ここまでは，単純グラフ(simple graph)とその主な性質について説明してきた．
しかし，実際に扱われるグラフはより複雑である．本節では簡潔に，一般的な複合グラフ(complex
graph)に関する形式的定義を紹介していく．

### Heterogeneousグラフ

ここまで説明してきた単純グラフは， $1$ 種類のノードと $1$ 種類のエッジしか含まないような同種的(homogeneous)なグラフであった．しかし，現実世界の多くの実用面では，「多種ノード間の多種な関係」をモデル化することが望まれる．図2.6に示すように，文献・引用を記述する学術ネットワークには，著者・論文・学会という $3$ 種類のノードが存在している．さらにこの図のノード間には異なる関係を表す様々なエッジも存在している．例えば，論文間の引用関係を表すエッジや，著者と論文間の著者関係を表すエッジなどがある．以下に，異種的(heterogeneous)なノードを含むグラフの定義を形式的に示す．

<div class="definition">
 
<strong>定義 2.34 Heterogeneousグラフ</strong>

Heterogeneous
グラフ $\g$ は，ノード集合 $\nodes = \left\{v\_1,\dots,v\_N\right\}$ とエッジ集合 $\edges=\left\{e\_1,\dots,e\_M\right\}$ で構成され，各ノードと各エッジには"タイプ"が関連付けられている．ノードタイプの集合を $\symbfscr{T}_n$ ，エッジタイプの集合を $\symbfscr{T}_e$ とする．そして各ノードと各エッジをそれぞれのタイプに対応付ける $2$ つの写像 $\phi\_n\colon \nodes\rightarrow\symbfscr{T}_n$ と $\phi\_e\colon \edges\rightarrow\symbfscr{T}_e$ が存在している．

</div>


![Heterogeneousグラフの例：学術情報ネットワーク](./fig/fig2_6.pdf){width="0.73\\linewidth"}

### 二部グラフ

二部グラフ $\sgraph$ におけるノード集合 $\nodes$ は，互いに素な $2$ つの部分集合 $\nodes\_1$ と $\nodes\_2$ に分割することができ， $\edges$ のすべてのエッジは， $\nodes\_1$ のノードと $\nodes\_2$ のノードを接続する．このように二部グラフは，異なるオブジェクト間の相互作用を把握するために広く用いられている．例えばAmazonのようなECサイトにおいては，図2.7に示すように，ユーザのクリック履歴を二部グラフとしてのモデル化が可能である．このとき，ユーザとアイテムは互いに素な $2$ つのノード集合とし，ユーザのクリックはそれらの間のエッジとみなすことになる．以下に二部グラフの形式的な定義を示す．

<div class="definition">
 
<strong>定義 2.35 二部グラフ</strong>

グラフ $\sgraph$ を考える． $\nodes = \nodes\_1\cup \nodes\_2$ かつ $\nodes\_1\cap \nodes\_2 = \emptyset$ が成り立ち，さらにすべての $e = (v^1_e,v^2_e)\in \edges$ に対して， $v^1_e\in \nodes\_1$ ,   $v^2_e\in \nodes\_2$ が満たされるとき，このグラフ $\sgraph$ は二部グラフであるという．

</div>


![二部グラフの例：オンラインショッピング](./fig/fig2_7.pdf){width="0.4\\linewidth"}

### Multidimensionalグラフ

実世界における多くの場面では，一組のノード間に複数の関係が同時に存在することがある．
このようなグラフの一例として，動画共有サイトYouTubeが挙げられる．YouTubeのユーザはお互いにチャンネル登録を行うことができ，それは一つの関係として見ることができる．また，他のユーザの動画を"共有"したり，"コメント"したりすることで，ユーザ同士は異なる種類の関係でつながることができる．他の例としてはAmazonなどのECサイトがある．Amazonのユーザは，"クリック"や"購入"，"レビュー"などの様々なアクションを介して，商品と相互に影響を与え合うことができる．
これらの複数の関係を持つグラフは，関係の種類を1つの次元として考慮することで，自然にMultidimensionalグラフとしてモデル化することができる．

<div class="definition">
 
<strong>定義 2.36 Multidimensional グラフ</strong>

Multidimensionalグラフは， $N$ 個のノードから成る集合 $\nodes = \left\{v\_1,\dots,v\_N\right\}$ および $D$ 個のエッジ集合 $\left\{\edges\_1,\dots,\edges\_D\right\}$ で構成される．各エッジ集合 $\edges\_d$ は，それぞれの $d$ 次元における，ノード間の $d$ 番目の関係タイプを表している．
また，これら $D$ 種類の関係は $D$ 個の隣接行列 $\symbf{A}^{(1)},\dots,\symbf{A}^{(D)}$ としても表現でき， $d$ 次元に対応する隣接行列 $\symbf{A}_d\in \mathbb{R}^{N\times N}$ は， $\nodes$ 中のノード間にあるエッジ集合 $\edges\_d$ を記述している．例えば， $\symbf{A}_d$ の $i,j$ 要素 $\symbf{A}_d[i,j]$ は，ノード $v\_i$ と $v\_j$ の間に次元 $d$ のエッジが存在するとき（ $(v\_i,v\_j)\in\edges\_d$ ）にのみ $1$ ，次元 $d$ のエッジが存在しない場合は $0$ となる．

</div>


### 符号付きグラフ

SNSの普及に伴い，正負のエッジを含む符号付きグラフはますます身近になってきている．符号付きグラフの例としてはFacebookやTwitterなどのSNSがあり，そこではユーザは他のユーザをブロックしたりフォロー解除したりできる．"ブロック"や"友達リスクからの削除"というアクションは，どちらもユーザ間の負のエッジと捉えることができる．図2.8は，ユーザをノード，friend関係（友だちリストへの追加）を正のエッジ，unfriend関係（友だちリストからの削除）を負のエッジとした符号付きグラフの一例である．
以下に，符号付きグラフの形式的な定義を示す． 
<div class="definition">
 
<strong>定義
2.37 符号付きグラフ</strong>

 $\nodes = \left\{v\_1,\dots,v\_N\right\}$ を $N$ 個のノードから成る集合， $\edges^{+}\subset\nodes\times\nodes$ と $\edges^{-}\subset\nodes\times\nodes$ をそれぞれ正と負のエッジ集合を表す．ただし，エッジは正または負のどちらか一方に属すこととし， $\edges^{+}\cap\edges^{-}=\emptyset$ を満たす．このとき， $\g = \left\{\nodes,\edges^{+},\edges^{-}\right\}$ は符号付きグラフである．これらのノード間の正・負エッジは符号付き隣接行列 $\symbf{A}$ で記述することができ，ノード $v\_i$ とノード $v\_j$ の間に正のエッジがあるとき $\symbf{A}_{i,j}=1$ ，負のエッジがあるとき $\symbf{A}_{i,j}=-1$ ，それ以外の場合 $\symbf{A}_{i,j}=0$ となる．

</div>


![符号付きグラフの例：友人関係](./fig/fig2_8.pdf){width="0.6\\linewidth"}

### ハイパーグラフ

これまで紹介したグラフは、エッジを介して $2$ つのノード間の情報のみを符号化していた．
しかし現実世界の多くの状況では，一対の関係を超える関係性を持つことがある．
図2.9では，論文間の関係を記述するハイパーグラフが示されている．
この例では特定の著者が $2$ つ以上の論文を発表することができるから，著者を，複数の論文(ノード)を結ぶ"ハイパーエッジ"とみなすことができる．
単純グラフに現れるエッジと比較して，ハイパーエッジは高次の関係を符号化できる．ハイパーエッジを持つグラフはハイパーグラフとよばれ，以下に，その形式的な定義を与えた．

<div class="definition">
 
<strong>定義 2.38 ハイパーグラフ</strong>

 $\nodes$ を $N$ 個のノード集合， $\edges$ をハイパーエッジ集合，そしてハイパーエッジ $e\_j$ の重みを $\symbf{W}[j,j]$ においた対角行列を $\symbf{W}\in \mathbb{R}^{|\edges|\times|\edges|}$ とする．このとき， $\g=\left\{\nodes, \edges, \symbf{W}\right\}$ をハイパーグラフと定義する．ハイパーグラフ $\g$ は，ノード $v\_i$ がエッジ $e\_j$ に現れる場合にだけ $\symbf{H}_{i,j}=1$ となる，接続行列 $\symbf{H}\in \mathbb{R}^{|\nodes|\times|\edges|}$ を用いて記述することができる．また，ノード $v\_i$ について，その次数を $\displaystyle d(v\_i)=\sum^{|\edges|}_{j=1}\symbf{H}_{i,j}$ と定義し，ハイパーエッジの次数を $\displaystyle d(e\_j) = \sum^{|\nodes|}_{i=1}\symbf{H}_{i,j}$ と定義する．さらに， $\symbf{D}\_e$ と $\symbf{D}\_v$ を，それぞれハイパーエッジとノードの(対角)次数行列を表すとする．

</div>


![ハイパーグラフの例：学術論文ネットワーク](./fig/fig2_9.pdf){width="0.7\\linewidth"}

### ダイナミックグラフ

前述したグラフは，観測時にノード間の接続が固定されている静的(static)なグラフである．
しかし，現実世界の多くの場面ではグラフは常に進化しており，グラフに新しいノードが追加されたり，新しいエッジが継続的に出現している．例えば，友だち関係を築けるようなFacebook等のSNSでは，ユーザは常に他のユーザと友好関係を築くことができ，また新規ユーザもいつでもFacebookに参加することができる．このような徐々に発展していくようなグラフは，各ノードや各エッジに時点(timestamp)が関連付けられた動的なグラフとしてモデル化できる．
図2.10にダイナミックグラフの模式図を示す．各エッジに時点が関連付けられていて，ノードの時点は，そのノードを含むエッジが出現した時点が与えられる．
以下に，ダイナミックグラフの形式的な定義を与えた．

![ダイナミックグラフの模式図](./fig/fig2_10.pdf){width="0.6\\linewidth"}


<div class="definition">
 
<strong>定義 2.39 ダイナミックグラフ</strong>

ダイナミックグラフ $\sgraph$ はノード集合 $\nodes=\left\{v\_1,\dots,v\_N\right\}$ とエッジ集合 $\edges=\left\{e\_1,\dots,e\_M\right\}$ で構成され，各ノードと各エッジの両方（またはどちらか一方）にはそれが出現した時刻を示す時点(timestamp)が関連付けられている．具体的には，各ノードおよび各エッジからそれぞれの出現時点への対応を与える $2$ つの写像 $\phi\_v$ および $\phi\_e$ が存在する．

</div>

実際には，各ノード・各エッジの時点を記録することは困難である．その代わりの方法として，グラフがどのように変化していくかを「時点を区切って」観測すればよい．
そのような場合，各時点 $t$ で観測されるグラフ $\g\_t$ の"スナップショット"を記録値として取得することができる．このようなダイナミックグラフは，複数のグラフのスナップショットで構成される"離散型ダイナミックグラフ"とよばれる．以下に，離散型ダイナミックグラフの形式的な定義を与えた．

<div class="definition">
 
<strong>定義 2.40 離散型ダイナミックグラフ</strong>

離散型ダイナミックグラフは，ダイナミックグラフの変化に沿って観測された $T$ 個のグラフのスナップショットで構成される．具体的には， $T$ 個のグラフスナップショットは，時点 $0$ に観測されたグラフを $\g\_0$ とし， $\left\{\g\_0,\dots,\g\_T\right\}$ と表すことができる．

</div>



[メインページ](../../index.markdown)

[章目次](./chap2.md)