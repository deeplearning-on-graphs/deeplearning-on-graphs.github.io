---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h1>第5章 グラフニューラルネットワーク</h1>

<h2>はじめに</h2>

<h2>目次</h2>
<ul style="list-style-type: none; padding-left:0;">
  <li>5.1 はじめに</li>
  <li>5.2 一般的な GNN のフレームワーク
    <ul>
      <li>5.2.1 ノードを対象としたタスクのフレームワーク</li>
      <li>5.2.2 グラフを対象としたタスクのフレームワーク</li>
    </ul>
  </li>
  <li>5.3 グラフフィルタ
    <ul>
      <li>5.3.1 スペクトル型グラフフィルタ
        <ul>
          <li>5.3.1.1 グラフの周波数フィルタリング</li>
          <li>5.3.1.2 スペクトル型グラフフィルタ</li>
          <li>5.3.1.3 チェビシェフ多項式とチェビシェフフィルタ</li>
          <li>5.3.1.4 GCN フィルタ：単純化された 1 次のチェビシェフフィルタ</li>
          <li>5.3.1.5 複数チャンネルのグラフ信号に対するグラフフィルタ</li>
        </ul>
      </li>
      <li>5.3.2 空間型グラフフィルタ
        <ul>
          <li>5.3.2.1 最初期のグラフニューラルネットワーク (GNN) のフィルタ</li>
          <li>5.3.2.2 GraphSAGE フィルタ</li>
          <li>5.3.2.3 GAT フィルタ</li>
          <li>5.3.2.4 ECC フィルタ</li>
          <li>5.3.2.5 GGNN フィルタ</li>
          <li>5.3.2.6 Mo フィルタ</li>
          <li>5.3.2.7 MPNN（空間型グラフフィルタの一般的なフレームワーク）</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>5.4 グラフプーリング
    <ul>
      <li>5.4.1 平坦グラフプーリング</li>
      <li>5.4.2 階層的グラフプーリング
        <ul>
          <li>5.4.2.1 ダウンサンプリング型プーリング</li>
          <li>5.4.2.2 スーパーノード型プーリング</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>5.5 GNN の学習
    <ul>
      <li>5.5.1 ノード分類における学習</li>
      <li>5.5.2 グラフ分類における学習</li>
    </ul>
  </li>
  <li>5.6 本章のまとめ</li>
  <li>5.7 参考文献</li>
</ul>
