# Task 13 - NumPy Random Sampling

## Objective
Learn NumPy random sampling functions for generating random numbers, selecting random values, shuffling data, and using random seeds.

## Requirements
- Python 3.x
- NumPy

```bash
pip install numpy
```

## Import
```python
import numpy as np
```

## 1. Random Integers
```python
import numpy as np
print(np.random.randint(1,10,size=5))
```

## 2. Random Floats
```python
import numpy as np
print(np.random.rand(5))
```

## 3. Random Matrix
```python
import numpy as np
print(np.random.rand(3,3))
```

## 4. Random Choice
```python
import numpy as np
fruits=["Apple","Banana","Orange","Mango"]
print(np.random.choice(fruits,size=2))
```

## 5. Random Integer Matrix
```python
import numpy as np
print(np.random.randint(1,100,size=(3,4)))
```

## 6. Shuffle
```python
import numpy as np
arr=np.array([1,2,3,4,5])
np.random.shuffle(arr)
print(arr)
```

## 7. Permutation
```python
import numpy as np
arr=np.array([1,2,3,4,5])
print(np.random.permutation(arr))
```

## 8. Seed
```python
import numpy as np
np.random.seed(42)
print(np.random.randint(1,10,5))
```

## 9. Student Marks Dataset
```python
import numpy as np
np.random.seed(10)
marks=np.random.randint(35,101,size=10)
print(marks)
```

## Complete Program
```python
import numpy as np

print(np.random.randint(1,10,size=5))
print(np.random.rand(5))
print(np.random.rand(3,3))

fruits=["Apple","Banana","Orange","Mango"]
print(np.random.choice(fruits,size=2))

print(np.random.randint(1,100,size=(3,4)))

arr=np.array([1,2,3,4,5])
np.random.shuffle(arr)
print(arr)

arr=np.array([1,2,3,4,5])
print(np.random.permutation(arr))

np.random.seed(42)
print(np.random.randint(1,10,5))

np.random.seed(10)
marks=np.random.randint(35,101,size=10)
print(marks)
```

## Conclusion
This task demonstrates NumPy random sampling using randint(), rand(), choice(), shuffle(), permutation(), and seed() to generate reproducible random data for Data Science.
# task13
