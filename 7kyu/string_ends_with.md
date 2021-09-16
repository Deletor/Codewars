
Codewars Python Solutions
---
## String ends with? <br>
---
Complete the solution so that it returns true if the first argument(string) passed in ends with the 2nd argument (also a string).

## Examples:
```
solution('abc', 'bc') # returns true
solution('abc', 'd') # returns false
```
---
### Given code
```python
def solution(string, ending):
    # your code here...
    pass
```
---
### Solution
```python
def solution(string, ending):
    if ending == '':
        return True
    elif string[-len(ending):] == ending:
        return True
    else: return False
```
