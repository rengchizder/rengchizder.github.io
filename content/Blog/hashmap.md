---
title: "Hashmap"
date: 2023-02-15T00:32:01+01:00
draft: false
---
Short explanation of counter in python.
```
from collections import Counter
c1 = Counter(li1)
c2 = Counter(li2)
print(c1 & c2 == c1) 
```
1. **Counter** is a subcalss of **Dict**, therefore, from Python3.7>=, **Counter** is insertion-ordered. 
2. `c1 & c2 == c1` implies that `c1` is a proper subset of `c2`.
3. **Dictionary** is equivalent to **hashmap** in **Java**. 

