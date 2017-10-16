# pybs
A painfully simple script to submit python commands to a cluster

```
pybs "import numpy as np; X = np.linalg.inv(np.random.randn(100,100)); np.savez('X.npz', X = X)"
```
