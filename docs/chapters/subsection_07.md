[メインページ](../../index.markdown)

[章目次](./chap2.md)
## 2.7. グラフを使った分析タスク

グラフを対象とした分析タスクには様々なものが提案されている．これらのタスクは主に $2$ つのカテゴリに分類される．

ノードに焦点を当てたタスク：

:   このタスクでは，通常，データ全体が $1$ つのグラフとして表現され，各ノードがデータサンプルとして扱われる．

グラフに焦点を当てたタスク：

:   このタスクでは，通常，データはグラフの集合で構成されており，各グラフがデータサンプルとして扱われる．

本節では，それぞれのグループに対する代表的なタスクを簡単に紹介する．

### ノードに焦点を当てたタスク

ノードに焦点を当てたタスクは，ノード分類，ノードの順位付け，リンク予測，コミュニティ検出など，数多く研究されている．ここでは，ノード分類やリンク予測という代表的な $2$ つタスクについて説明していく．

#### ノード分類

現実世界に現れる多くのグラフでは，ノードには有用な情報が関連付けられており，これらの情報はノードのラベルとして扱われることが多い．例えばSNSでは，年齢や性別，職業などのユーザの人口統計的特性や，ユーザの趣向や趣味などがそのラベルの例である．
これらのラベルは通常ノードを特徴づけるのに役立ち，多くの重要な場面で活用できる．
例えば，FacebookなどのSNSでは，趣向や趣味に関連するラベルを利用することで，関連するアイテム（ニュースやイベントなど）をユーザに"おすすめ"することができる．
しかし現実的には，全てのノードのラベルを揃えることが困難な場合が多いのが現状である．例えば，Facebookでは人口統計的プロフィールを完全に提供しているユーザは全体のうちの $1\%$ 未満である．
そのため，一部のノードにしかラベルが付与されていないグラフが与えられたとき，ラベルのないノードのラベルを推測する課題が生じてくる．この課題がグラフ上のノード分類問題を扱う動機となっている．

<div class="definition">
 
<strong>定義 2.42 ノード分類</strong>


ノード集合 $\mathcal{V}$ とエッジ集合 $\mathcal{E}$ を持つグラフを $\mathcal{G} = \left\{\mathcal{V},\mathcal{E}\right\}$ と表す． $\mathcal{V}$ のノードの中にはラベルが貼られているものがあり，このラベルが付いたノード集合を $\mathcal{V}_l\subset\mathcal{V}$ と表す．残りのノードはラベルを持たないので，このラベルがないノード集合を $\mathcal{V}_u$ と表す．これらの集合は， $\mathcal{V}_l\cup\mathcal{V}_u = \mathcal{V}$ かつ $\mathcal{V}_l\cap\mathcal{V}_u = \emptyset$ を満たす．ノード分類タスクの目的は，ラベルのないノード( $v\in \mathcal{V}_u$ )のラベルを予測する写像 $\phi$ を， $\mathcal{G}$ と $\mathcal{V}_l$ のラベルを活用して学習することにある．

</div>

上記の定義は単純グラフに対するものであり，2.6節で紹介した多様な属性を持つグラフなどの複雑グラフにも容易に拡張できる．

<div class="eg">
 
<strong>例 2.43 Flickrにおけるノード分類</strong>

Flickrは，ユーザが個人で撮影した写真を管理できる画像管理プラットフォームであり，かつユーザ同士がフォローし合えるようなSNSとしての役割も担っている．したがって，Flickr上のユーザ同士の繋がりはグラフを形成する．さらに，Flickrのユーザは，"Black
and White"(白黒写真)や"The Fog and The Rain"(霧と雲の写真)，"Dog
World"(犬の写真)など，関心グループに登録することができる．これらのグループへの登録情報はユーザの興味を示しており，それをラベルとして使用することができる．ユーザは複数のグループに登録することができるので，各ユーザに複数のラベルを関連付けることができる．グラフ上の"マルチラベルノード分類問題"は，ユーザが興味を持っているがまだ登録していない潜在的なグループを予測するのに役立つ．このようなFlickrのデータセットの詳細については，Tang
and Lie(2009)を参照せよ． 
</div>


#### リンク予測

現実世界に出会う多くの場面において，グラフはエッジが欠落しており，完全なものではない．観測されたグラフで欠落しているエッジが発生するのは，ノード間の接続の一部が存在しているが観測や記録がされていないことが一つの原因として考えられる．また他方で，多くのグラフは当然ながら変化しており，そこから欠落エッジが発生していくこともある．例えばFacebookのようなSNSでは，ユーザは常に他のユーザと友だちになることができたり，学術的な共同研究を表すグラフでは，ある著者が他の著者と常に新しい共同研究関係を構築し得る．こうして欠落したエッジを推測・予測することは，友達の推薦(Adamic
and Adar, 2003)やナレッジグラフ補完(Nickel *et al*.,
2015)，犯罪情報分析(Berlusconi *et al*.,
2016)など，多くの応用面で恩恵をもたらしている．
以下にリンク予測問題の形式的な定義を与えた． 
<div class="definition">
 
<strong>定義
2.44 リンク予測</strong>

 $\mathcal{V}$ をノード集合， $\mathcal{E}$ をエッジ集合とするグラフを $\mathcal{G} = \left\{\mathcal{V},\mathcal{E}\right\}$ とする． $\mathcal{V}$ 中のノード間の可能な全てのエッジを $\mathcal{M}$ とすると， $\mathcal{M}$ を全体とした $\mathcal{E}$ の補集合を $\mathcal{E}^{\prime} = \mathcal{M} - \mathcal{E}$ と表す．集合 $\mathcal{E}^{\prime}$ にはノード間の未観測のエッジが含まれる．リンク予測タスクの目標は，最も可能性の高いエッジを予測することである．具体的には， $\mathcal{E}^{\prime}$ 内の各エッジにスコアを割り当てることができる．これは，それらのエッジが存在しているか，又は将来現れる可能性がどの程度あるかを示している．

</div>

なお，この定義は単純なグラフについて述べたものであり，2.6節で紹介した複雑グラフに簡単に拡張できる．例えば，符号付きグラフの場合，エッジの存在に加えてその符号を予測し，ハイパーグラフでは，複数のノード間の関係を記述するハイパーエッジを推測することになる．

<div class="eg">
 
<strong>例 2.45
DBLPサイトにおける新たな共同研究の予測</strong>

DBLPは，コンピュータサイエンス分野の研究論文を包括的に収集・管理しているオンラインの学術文献データベースサイトである．DBLPに収録されている論文から，著者をノードとする共著グラフを作成できる．このグラフでは，一組の著者がDBLPに収録された共著論文を $1$ 件以上持っている場合，彼らの間につながりがあるとみなされる．これまで共著の経験がない著者同士がどのような新しい共同研究を行うかを予測することは，興味深いリンク予測問題である．リンク予測の研究に用いられた大規模なDBLP共同研究データセットの詳細については，Yang
and Leskovec(2015)を参照せよ． 
</div>


### グラフに焦点を当てたタスク

グラフ分類やグラフマッチング，グラフ生成など，グラフに特化したタスクは数多く存在する．以下では最も代表的なタスクである"グラフ分類"について述べていく．

#### グラフ分類

(前述した)ノード分類では，グラフ内の各ノードがサンプルデータとして扱われており，ラベルのないノードにラベルを付与することが目的であった．しかし一方で，別の応用として，各サンプルがグラフとして表現されることもある．

例としてケモインフォマティクスにおける応用を考える．この分野では，化学分子は，原子をノード，それらの間の化学結合をエッジとしたグラフとして表現できる．
さらにこれらの化学分子は，溶解度や毒性などの異なる性質を持つことがあり，この性質をグラフ全体に与えられる一つのラベルとして扱うことができる．実際には，新しく発見された化学物質の性質を自動的に予測したい状況がある．この目的は，ラベルのないグラフのラベルを予測するグラフ分類タスクによって達成できる．グラフの構造が複雑であるため，グラフ分類は従来の分類手法では対処できず，グラフに特化した試みが必要とされる．以下にグラフ分類の形式的な定義を示す．

<div class="definition">
 
<strong>定義 2.46 グラフ分類</strong>


 $y_i$ をグラフ $\mathcal{G}_i$ のラベルとする，ラベル付きグラフの集合 $\mathcal{D} = \left\{(\mathcal{G}_i, y_i)\right\}$ が与えられたとき，グラフ分類タスクの目的は， $\mathcal{D}$ を使ってラベルのないグラフが持つラベルを予測するような写像 $\phi$ を学習することにある．

</div>

上記の定義では，グラフに関連する可能性のある付加的な情報は指定しなかった．例えば，特定の状況では，グラフ分類に利用できる特定の特徴が各ノードに関連付けれられていることがある．

<div class="eg">
 
<strong>例 2.47
タンパク質の構造の酵素/非酵素への分類</strong>

タンパク質は，アミノ酸をノードとするグラフで表すことができ， $2$ つのノード間距離が $6$ Å
( $=10^{-10}\textrm{m}$ )未満であればエッジが形成される．酵素はタンパク質の一種で，生化学反応を触媒する生体触媒として機能する．また，酵素は，生化学反応を触媒する役割を持つタンパク質の一種である．あるタンパク質が与えられたとき，それが酵素であるかどうかを予測することは，各タンパク質のラベルが酵素か非酵素かのグラフ分類タスクとして扱うことができる．

</div>



[メインページ](../../index.markdown)

[章目次](./chap2.md)

[前の章へ](./subsection_06.md) [次の章へ](./subsection_08.md)