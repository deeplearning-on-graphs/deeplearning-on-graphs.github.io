---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h2>本書の概要</h2>
<div style="display: flex; align-items: center;">
    <div style="flex: 0.3;">
        <img src="./cover.jpg" alt="" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 1; margin-left: 20px;">
    <p>世界は「グラフ」でできている。ソーシャルネットワーク、交通ネットワーク、タンパク質の相互作用など、身の回りの様々な現象は、ノード(頂点)とエッジ(辺)から構成されるグラフによって記述することができる。本書はこのグラフを深層学習(ディープラーニング)に適用した「グラフ深層学習」を、初学者にも分かりやすく解説した入門書である。グラフ理論や深層学習の基礎からはじめ、グラフニューラルネットワーク(GNN)の理論的な側面やその実践的な応用例を幅広く取り上げている。自然言語処理、画像処理、データマイニング、生化学・ヘルスケアなど、様々な分野でのGNNの活用が理解できるようになってる。GNNに興味を持つ学生や研究者、さらには実際の業界でGNNを応用したいと考えている専門家にとって、理解の手引きとなる一冊である。</p>
    </div>
</div>

<p>Amazonのリンクは<a href="https://amzn.asia/d/6agPggA">こちら</a></p>
<p>プレアデス出版社のリンクは<a href="http://www.pleiades-publishing.co.jp/genre/kakuritsu.html#bk05">こちら</a></p>

## 目次
- 第1章 イントロダクション（[はじめに](./chap/1_introduction.markdown) / [参考文献](./chap/1_ref.markdown)）
### 第Ⅰ部
- 第2章 グラフ理論の基礎（[はじめに](./chap/2_introduction.markdown) / [参考文献](./chap/2_ref.markdown)）
- 第3章 深層学習の基礎（[はじめに](./chap/3_introduction.markdown) / [参考文献](./chap/3_ref.markdown)）
### 第Ⅱ部
- 第4章 グラフ埋め込み（[はじめに](./chap/4_introduction.markdown) / [参考文献](./chap/4_ref.markdown)）
- 第5章 グラフニューラルネットワーク（[はじめに](./chap/5_introduction.markdown) / [参考文献](./chap/5_ref.markdown)）
- 第6章 グラフニューラルネットワークの敵対的ロバスト性（[はじめに](./chap/6_introduction.markdown) / [参考文献](./chap/6_ref.markdown)）
- 第7章 グラフニューラルネットワークのスケーラビリティ（[はじめに](./chap/7_introduction.markdown) / [参考文献](./chap/7_ref.markdown)）
- 第8章 複雑グラフ上のグラフニューラルネットワーク（[はじめに](./chap/8_introduction.markdown) / [参考文献](./chap/8_ref.markdown)）
- 第9章 GNNの枠を超えて：グラフ上に関するその他の深層学習モデル（[はじめに](./chap/9_introduction.markdown) / [参考文献](./chap/9_ref.markdown)）
### 第Ⅲ部
- 第10章 自然言語処理におけるグラフニューラルネットワークの応用（[はじめに](./chap/10_introduction.markdown) / [参考文献](./chap/10_ref.markdown)）
- 第11章 画像処理におけるグラフニューラルネットワーク（[はじめに](./chap/11_introduction.markdown) / [参考文献](./chap/11_ref.markdown)）
- 第12章 データマイニングにおけるグラフニューラルネットワーク（[はじめに](./chap/12_introduction.markdown) / [参考文献](./chap/12_ref.markdown)）
- 第13章 生化学・ヘルスケア分野におけるグラフニューラルネットワーク（[はじめに](./chap/13_introduction.markdown) / [参考文献](./chap/13_ref.markdown)）
### 第Ⅳ部
- 第14章 グラフニューラルネットワークに関する発展的な話題（[はじめに](./chap/14_introduction.markdown) / [参考文献](./chap/14_ref.markdown)）
- 第15章 グラフニューラルネットワークにおける発展的な応用例（[はじめに](./chap/15_introduction.markdown) / [参考文献](./chap/15_ref.markdown)）
- [参考文献（全章）](./all_ref.markdown)
    - [PDF](./References.pdf){:target="_blank"} / [CSV](./references_books.csv){:target="_blank"}

## 読書アシスタント
実験的に，「本の内容について直接質問し，その答えを受ける」ことを可能にしたサービスを公開しております．

- 読書アシスタントは[こちら](https://chat.openai.com/g/g-yDqZojV1t-gurahushen-ceng-xue-xi-du-shu-asisutanto)
    - ChatGPT Plusのアカウントが必要になります。
        - 使用制限（時間あたりのクエリ回数）があるのでご注意ください
    - 本アシスタントは間違いを犯すことがあります。自身が持つ知識領域と直接縫い合わせながらご活用ください。
    - サービス元の仕様変更等により、予告なく本アプリケーションの提供を変更したり、取りやめる場合がございます。ご了承ください。
        - 技術進展の状況を見て，性能の良い技術に鞍替えすることもあります．
- [読書アシスタントの使い方](https://note.com/dl_on_graphs/n/n4f0bbf0ff054)

## 誤植情報
誤植・修正情報は[こちら](./errata.markdown)．

## 補助資料（応用数学教材）

理解の手助けのため，拙訳である「解きながら学ぶ 完全独習 応用数学(2023)」の一部章を公開しています（本書の内容の形式を少々変更しています）．<br>
本書は，例題を解きながら本文を理解していくというスタイルの教材になっています．
学習の補助にご活用ください．

- 第1章：予備知識の復習：微積分，行列，複素数
    - [本文(PDF)](./admath_basic_cal_text.pdf){:target="_blank"} / [例題(PDF)](./admath_basic_cal_exercise.pdf){:target="_blank"}

- 第15章：線形代数
    - [本文(PDF)](./admath_linear_algebra_text.pdf){:target="_blank"} / [例題(PDF)](./admath_linear_algebra_exercise.pdf){:target="_blank"}

## 訳者略歴
#### 宮原 太陽（みやはら たいよう）
慶應義塾大学環境情報学部卒．
スカイウィル株式会社にて，データサイエンティストとして分析業務に従事．

#### 中尾 光孝（なかお みつたか）
東京大学理学部物理学科卒，東京大学大学院理学系研究科物理学専攻修了．
博士（理学）．証券会社にて，クオンツアナリスト・データサイエンティストとしてネットワークデータを活用した分析業務に従事．

## 問い合わせ先
- deeplearning.on.graphs@gmail.com
- [X](https://twitter.com/deepL_on_graphs)
