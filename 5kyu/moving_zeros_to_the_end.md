
Codewars Python Solutions
---
## Moving zeros to the end <br>
---
Write an algorithm that takes an array and moves all of the zeros to the end, preserving the order of the other elements.
```
move_zeros([1, 0, 1, 2, 0, 1, 3]) # returns [1, 1, 2, 1, 3, 0, 0]

```
---
### Given code
```python
def move_zeros(array):
    return array
```
---
### Solution
```python
def move_zeros(array):
  zero = []
  new = []
  n = len(array)
  for i in range(n):
    if array[i] != 0:
      new.append(array[i])
    else:
      zero.append(array[i])
  array = new + zero
  return array
```
