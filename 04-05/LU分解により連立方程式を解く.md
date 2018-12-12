```
>>> import numpy as np
>>> a = np.array([[3, 1, 1], [1, 2, 1], [0, -1, 1]])
>>> b = np.array([1, 2, 3])
>>> a
array([[ 3,  1,  1],
       [ 1,  2,  1],
       [ 0, -1,  1]])
>>> b
array([1, 2, 3])
scipy.linalgモジュールのインポート
>>> from scipy import linalg
LU分解の実行
>>> lu, p = linalg.lu_factor(a)
>>> linalg.lu_solve((lu, p), b)
array([-0.57142857, -0.14285714,  2.85714286])
```
