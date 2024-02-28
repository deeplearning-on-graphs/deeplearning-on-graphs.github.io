---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h1>第6章 GNNの敵対的ロバスト性</h1>

<h2>はじめに</h2>

<h2>目次</h2>
<ul style="list-style-type: none; padding-left:0;">
  <li>6.1 はじめに</li>
  <li>6.2 グラフへの敵対的攻撃
    <ul>
      <li>6.2.1 敵対的攻撃の分類
        <ul>
          <li>6.2.1.1 攻撃者の行動範囲に基づく分類</li>
          <li>6.2.1.2 摂動の種類に基づく分類</li>
          <li>6.2.1.3 攻撃者の目標に基づく分類</li>
          <li>6.2.1.4 標的モデルの知識に基づく分類</li>
        </ul>
      </li>
      <li>6.2.2 ホワイトボックス攻撃
        <ul>
          <li>6.2.2.1 PGD トポロジー攻撃</li>
          <li>6.2.2.2 積分勾配に基づく攻撃</li>
        </ul>
      </li>
      <li>6.2.3 グレーボックス攻撃
        <ul>
          <li>6.2.3.1 Nettack</li>
          <li>6.2.3.2 Metattack</li>
        </ul>
      </li>
      <li>6.2.4 ブラックボックス攻撃
        <ul>
          <li>6.2.4.1 RL-S2V</li>
          <li>6.2.4.2 ReWatt</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>6.3 敵対的攻撃に対する防御
    <ul>
      <li>6.3.1 グラフの敵対的学習
        <ul>
          <li>6.3.1.1 グラフ構造を用いた敵対的学習</li>
          <li>6.3.1.2 ノード特徴量を用いた敵対的学習</li>
          <li>6.3.1.3 グラフ構造とノード特徴量の両方を用いた敵対的学習</li>
        </ul>
      </li>
      <li>6.3.2 グラフの純化
        <ul>
          <li>6.3.2.1 特徴量の類似度が低いエッジの除去によるグラフ純化</li>
          <li>6.3.2.2 隣接行列の低ランク近似によるグラフの純化</li>
        </ul>
      </li>
      <li>6.3.3 グラフアテンション防御
        <ul>
          <li>6.3.3.1 RGCN：正規分布による隠れ表現のモデル化</li>
          <li>6.3.3.2 PA-GNN：クリーンなグラフから作る敵対的エッジを用いた学習</li>
        </ul>
      </li>
      <li>6.3.4 グラフ構造学習</li>
    </ul>
  </li>
  <li>6.4 本章のまとめ</li>
  <li>6.5 参考文献</li>
</ul>
