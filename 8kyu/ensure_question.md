
Codewars Python Solutions
---
## Ensure question <br>
---
Given a string, write a function that returns the string with a question mark ("?") appends to the end, unless the original string ends with a question mark, in which case, returns the original string.

For example **(Input --> Output)**
```
"Yes" --> "Yes?" 
"No?" --> "No?"
```

---
### Given code
```python
def ensure_question(s):
    # Code here
```
---
### Solution
```python
def ensure_question(s):
    if s[len(s)-1:len(s)] == '?':
        return s
    else:
        return s + '?'
```
