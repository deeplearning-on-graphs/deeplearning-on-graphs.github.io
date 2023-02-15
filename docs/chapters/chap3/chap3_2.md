<script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax:{inlineMath:[['\$','\$'],['\\(','\\)']],processEscapes:true},CommonHTML: {matchFontHeight:false}});</script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>

[メインページ](../../index.markdown)

# 3. 深層学習の基礎
## [3.1 はじめに](./chap3_1.md)

## 3.2 深層順伝播型ネットワーク

順伝播型ネットワークは, 多くの重要な深層学習技術の基礎となっている.
例えば分類問題において,
理想的な分類器である $f^{\ast}(x)$ は与えられた入力 $\mathbf{x}$ を正解の分類 $\mathbf{y}$ に対応づける.
この場合,
順伝播型ネットワークでは理想的な分類器 $f^{\ast}(x)$ をうまく近似できるような写像 $f(\mathbf{x} \mid \Theta)$ を見つける.
具体的には, 順伝播型ネットワークを学習する目的は,
 $f^{\ast}(x)$ の最良の近似値を得ることができるパラメータ $\Theta$ の値を学習するということになる.


## [3.3 畳み込みニューラルネットワーク](./chap3_3.md)
