```
>>> import numpy as np
>>> np.sqrt(1.000000001**2 - 4 * 1 * 0.000000001)
0.999999999
```
```
>>> tmp = np.sqrt(1.000000001**2 - 4 * 1 * 0.000000001)
>>> tmp
0.999999999
>>> b = 1.000000001
>>> b
1.000000001
有効桁数の減少
>>> -b + tmp
-2.0000000544584395e-09
```
