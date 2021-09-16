
Codewars Python Solutions
---
## Pyramid Array<br>
---
Write a function that when given a number >= 0, returns an Array of ascending length subarrays.
```python
pyramid(0) => [ ]
pyramid(1) => [ [1] ]
pyramid(2) => [ [1], [1, 1] ]
pyramid(3) => [ [1], [1, 1], [1, 1, 1] ]
```
Note: the subarrays should be filled with ```1```s

---
### Given code
```python
def pyramid(n):
    # your code here
```
---
### Solution
```python
def pyramid(n):
    return [[1 for _ in range(i)] for i in range(1, n+1)]
```
