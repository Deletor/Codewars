
Codewars Python Solutions
---
## Unique in order <br>
---
Implement the function unique_in_order which takes as argument a sequence and returns a list of items without any elements with the same value next to each other and preserving the original order of elements.

## For example:
```
unique_in_order('AAAABBBCCDAABBB') == ['A', 'B', 'C', 'D', 'A', 'B']
unique_in_order('ABBCcAD')         == ['A', 'B', 'C', 'c', 'A', 'D']
unique_in_order([1,2,2,3,3])       == [1,2,3]
```

---
### Given code
```python
def unique_in_order(iterable):
    pass
```
---
### Solution
```python
from itertools import groupby
def unique_in_order(iterable):
    return [elem for elem, _ in groupby(iterable)]
```
