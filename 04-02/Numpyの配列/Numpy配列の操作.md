```
>>> import numpy as np
>>> a = np.array([2, 3, 5, 7, 8])
先頭の要素
>>> a[0]
2
インデックス1~2の要素
>>> a[1:3]
array([3, 5])
インデックス3~(5-1)=4までの要素
>>> a[2:-1]
array([5, 7])
arange関数による配列の作成
>>> b = np.arange(5)
>>> b
array([0, 1, 2, 3, 4])
ステップを0.2にする
>>> c = np.arange(1, 3, 0.2)
>>> c
array([1. , 1.2, 1.4, 1.6, 1.8, 2. , 2.2, 2.4, 2.6, 2.8])
型の確認
>>> a.dtype
dtype('int64')
>>> c.dtype
dtype('float64')
作成時に型を指定する
>>> d = np.array([1, 2, 3], dtype=np.float64)
>>> d
array([1., 2., 3.])
>>> d.dtype
dtype('float64')
引数に浮動小数点数を指定
>>> e = np.arange(5.)
>>> 3
3
>>> e
array([0., 1., 2., 3., 4.])
>>> e.dtype
dtype('float64')
```