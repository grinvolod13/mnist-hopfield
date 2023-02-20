# MNIST-Hopfield
MNIST dataset classification with Hopfield network

```python
test_count = 10000
scale = 0.6
q = 0
method='strokey'

model = Hopfield()
```
Testing:

    100%|████████████████████████████████████████████████████████████████████████████| 10000/10000 [39:54<00:00,  4.18it/s]
```
    Result with Dice(F1) score classifier
    0: 78%, 1019 tests
    1: 80%, 1095 tests
    2: 14%, 996 tests
    3: 47%, 1002 tests
    4: 39%, 971 tests
    5: 22%, 896 tests
    6: 70%, 994 tests
    7: 64%, 1079 tests
    8: 6%, 964 tests
    9: 50%, 984 tests
     total: 48.33%
```
