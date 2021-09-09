
Codewars Python Solutions
---
## Beginner Series #3 Sum of Numbers <br>
---
Given two integers ```a``` and ```b```, which can be positive or negative, find the sum of all the integers between and including them and return it. If the two numbers are equal return a or b.

Note: a and b are not ordered!
```python
Examples
get_sum(1, 0) == 1   // 1 + 0 = 1
get_sum(1, 2) == 3   // 1 + 2 = 3
get_sum(0, 1) == 1   // 0 + 1 = 1
get_sum(1, 1) == 1   // 1 Since both are same
get_sum(-1, 0) == -1 // -1 + 0 = -1
get_sum(-1, 2) == 2  // -1 + 0 + 1 + 2 = 2
```
---
### Given code
```python
def get_sum(a,b):
    #good luck!
```
---
### Solution
```python
def get_sum(a,b):
  max_num = max(a, b) + 1
  min_num = min(a ,b)

  num = 0
  for i in range(min_num,max_num):
    num += i
  return num
```
