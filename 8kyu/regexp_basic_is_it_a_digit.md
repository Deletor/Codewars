
Codewars Python Solutions
---
## Regexp Basics - is it a digit? <br>
---
Implement ```String#digit?``` (in Java ```StringUtils.isDigit(String)```), which should return ```true``` if given object is a digit (0-9), ```false``` otherwise.
---
### Given code
```python
def is_digit(n):
    #your code here
```
---
### Solution
```python
def is_digit(n):
    if n.isdigit() and int(n) >= 0 and int(n) <= 9:
        return True
    else: 
        return False
```
