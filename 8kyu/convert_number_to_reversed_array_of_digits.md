
Codewars Python Solutions
---
## Convert number to reversed array of digits <br>
---
### Convert number to reversed array of digits
Given a random non-negative number, you have to return the digits of this number within an array in reverse order.

### Example:
```
348597 => [7,9,5,8,4,3]
```
---
### Given code
```python
def digitize(n):
    return
```
---
### Solution
```python
def digitize(n):
    return [int(s) for s in str(n)[::-1]]
```
