
Codewars Python Solutions
---
## Square(n) Sum <br>
---
Complete the square sum function so that it squares each number passed into it and then sums the results together.

For example, for ```[1, 2, 2]``` it should return ```9``` because ```1^2 + 2^2 + 2^2 = 9```.

---
### Given code
```python
def square_sum(numbers):
    #your code here
```
---
### Solution
```python
def square_sum(numbers):
    n = 0
    for i in numbers:
        n += i * i
    return n
```
