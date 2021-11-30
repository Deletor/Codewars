
Codewars Python Solutions
---
## Sum Mixed Array <br>
---
Given an array of integers as strings and numbers, return the sum of the array values as if all were numbers.

Return your answer as a number.

---
### Given code
```python
def sum_mix(arr):
    #your code here
```
---
### Solution
```python
def sum_mix(arr):
    a = 0
    for i in arr:
        a += int(i)
    return a
```
