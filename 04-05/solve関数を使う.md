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
>>> np.linalg.solve(a, b)
array([-0.57142857, -0.14285714,  2.85714286])
```
