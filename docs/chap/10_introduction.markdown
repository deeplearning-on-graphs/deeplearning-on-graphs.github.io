---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<a href="./">メインページ</a>

<h1>第10章 自然言語処理分野におけるGNN</h1>

<h2>はじめに</h2>
グラフは，**自然言語処理**(NLP; Natural Language Processing)における言語構造を表現するために幅広く活用されている． 例えば，構文木は与えられた文のフレーズ構造をグラフとして表現し， また依存構造木は文法的依存関係（構文的関係）を木構造のグラフとして符号化する(Jurafsky and Martin, 2000)． また，抽象的意味表現(AMR; Abstract Meaning Representation)は，文章が伝える内容を，プログラムが容易に探索できるような「根(root)ノードを持つラベル付きのグラフ」として表現する(Banarescu *et al*., 2013)． これらの自然言語のグラフ表現は，豊富な意味情報や構文情報を明確な構造的方法で伝えている． また，これらのグラフには上述したものの他に，特定のタスクに特化した設計されたグラフも含まれている．

このようなグラフを活用したグラフニューラルネットワーク(GNN)は様々なNLPタスクで採用されている．具体的にGNNは，以下のような，多くのNLPタスクの性能向上に貢献している：

-   **意味役割のラベリング**

    -   参考文献：Marcheggiani and Titov.(2017)

-   **(マルチホップ)質問応答(QA)**

    -   参考文献：De Cao *et al*.(2019); Cao *et al*.(2019); Song *et al*.(2018a); Tu *et al*.(2019)

-   **関係抽出**

    -   参考文献： Zhang *et al*.(2018c); Fu *et al*.(2019); Guo *et al*.(2019); Zhu *et al*.(2019b); Sahu *et al*.(2019); Sun *et al*.(2019a); Zhang *et al*.(2019d)\

-   **ニューラル機械翻訳**

    -   参考文献：Marcheggiani *et al*.(2018); Beck *et al*.(2018)

-   **Graph-to-Sequence**

    -   参考文献：Cohen (2019); Song *et al*.(2018b); Xu *et al*.(2018b)

上記の他に，多元的で複雑な関係性を符号化した**知識グラフ**についても，自然言語処理(NLP)タスクに広く採用されている． そしてこのような知識グラフを一般化したグラフニューラルネットワーク(GNN)モデルに関しても多くの研究が存在している(Hamaguchi *et al*., 2017; Schlichtkrull *et al*., 2018; Nathani *et al*., 2019; Shang *et al*., 2019a; Wang *et al*., 2019c; Xu *et al*., 2019a)．

本章では，「意味役割のラベリング」，「ニューラル機械翻訳」，「関係抽出」，「質問応答」，「グラフ構造データからシーケンスデータに変換する学習」といった例を挙げ，GNNがどのようにNLPタスクに適用されているかを見ていく． また，知識グラフに特化したGNNについても紹介していく．

<h2>目次</h2>
<ul style="list-style-type: none; padding-left:0;">
  <li>10.1 はじめに</li>
  <li>10.2 意味役割のラベリング（SRL）</li>
  <li>10.3 ニューラル機械翻訳</li>
  <li>10.4 関係抽出</li>
  <li>10.5 質問応答 (QA)
    <ul>
      <li>10.5.1 マルチホップ QA タスク</li>
      <li>10.5.2 Entity-GCN
        <ul>
          <li>10.5.2.1 Entity グラフ</li>
          <li>10.5.2.2 Entity グラフ上での Entity-GCN によるマルチステップ推論</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>10.6 Graph-to-Sequence 学習
    <ul>
      <li>10.6.1 Graph2Seq におけるエンコーダーおよびデコーダー</li>
    </ul>
  </li>
  <li>10.7 知識グラフ上の GNN
    <ul>
      <li>10.7.1 方法 1：知識グラフ用のグラフフィルタ設計</li>
      <li>10.7.2 方法 2：知識グラフの単純グラフへの変換</li>
      <li>10.7.3 知識グラフの補完</li>
    </ul>
  </li>
  <li>10.8 本章のまとめ</li>
  <li>10.9 参考文献</li>
</ul>
<br>
<a href="./">メインページ</a>
