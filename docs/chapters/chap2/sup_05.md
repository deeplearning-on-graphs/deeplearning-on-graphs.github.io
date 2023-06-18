# 2.5 サポートページ
注：このサポートページは、内容の理解のために訳者側で作成したものです。

## グラフフーリエ変換
グラフフーリエ変換は、グラフ上の信号を、ラプラシアン行列の固有ベクトル（グラフフーリエ基底）による級数に分解する処理と考えることができます。具体的には、グラフ信号 $\symbf{f}$ のグラフフーリエ変換は次のように定義されます：

$$
\hat{\symbf{f}} = \symbf{U}^{T}\symbf{f}
$$

ここで、 $\symbf{U}$ はラプラシアン行列の固有ベクトルを列ベクトルとして並べた行列、 $\symbf{f}$ はグラフ上の信号を表します。
得られた $\hat{\symbf{f}}$ は、各グラフフーリエ基底が信号 $\symbf{f}$ に対してどれだけ寄与しているかを表す係数（グラフフーリエ係数）を要素とするベクトルです。

### numpy
```python
import numpy as np

# 定数グラフの定義
A = np.array([
    [0, 1, 0, 0, 1, 1],
    [1, 0, 1, 0, 1, 0],
    [0, 1, 0, 1, 0, 0],
    [0, 0, 1, 0, 1, 1],
    [1, 1, 0, 1, 0, 0],
    [1, 0, 0, 1, 0, 0]
])

# 次数行列の計算
D = np.diag(np.sum(A, axis=1))

# ラプラシアン行列の計算
L = D - A

# グラフ信号の定義（ここではランダムなベクトルを使用）
f = np.random.rand(6)

# 固有値と固有ベクトルの計算
eigvals, eigvecs = np.linalg.eig(L)

# グラフフーリエ変換の計算
f_hat = eigvecs.T @ f

print(f_hat)
```

### networkx

[メインページ](../../index.markdown)

[章目次](./chap2.md)