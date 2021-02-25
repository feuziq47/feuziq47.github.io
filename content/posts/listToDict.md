---
title: "ListToDict"
date: 2021-02-26T00:22:09+09:00
draft: true
---

## 파이썬 List to Dict

### 1. Dictionary Comprehesion

```python
A = ['가', '나', '다']
dictionary = {string: i for i, num in enumerate(A)}
print(dictionary)
# {'가':0 , '나':1, '다':2}
```

### 2. dict.fromkeys(key, value)

```python
A = ['가', '나', '다']
dictionary = dict.fromkeys(A, 0)
print(dictionary)
# {'가':0 , '나':0, '다':0}
```

### 3. zip 사용하여 묶기

```python
A = ['가', '나', '다']
B = [0, 1, 2]
dictionary = dict(zip(A, B))
# {'가':0 , '나':1, '다':2}
```

