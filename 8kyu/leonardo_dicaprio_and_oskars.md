
Codewars Python Solutions
---
## Leonardo Dicaprio and Oscars <br>
---
You have to write a function that describe Leo:
```python
def leo(oscar):
  pass
```

- if oscar was (integer) 88, you have to return "Leo finally won the oscar! Leo is happy".
- if oscar was 86, you have to return "Not even for Wolf of wallstreet?!"
- if it was not 88 or 86 (and below 88) you should return "When will you give Leo an Oscar?"
- if it was over 88 you should return "Leo got one already!"

---
### Given code
```python
def leo(oscar):
    pass
```
---
### Solution
```python
def leo(oscar):
    if oscar == 88: return "Leo finally won the oscar! Leo is happy"
    elif oscar == 86: return "Not even for Wolf of wallstreet?!"
    elif oscar > 88: return "Leo got one already!"
    else: return "When will you give Leo an Oscar?"
```
