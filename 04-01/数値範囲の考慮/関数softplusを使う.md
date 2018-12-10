```
>>> import softplus
>>> softplus.softplus(-1)
0.31326168751822286
>>> softplus.softplus(0)
0.6931471805599453
>>> softplus.softplus(1000)
/Users/takyshu98/tmp/essence-of-machine-learning/04-01/softplus.py:4: RuntimeWarning: overflow encountered in exp
  return np.log(1 + np.exp(x))
inf
```
