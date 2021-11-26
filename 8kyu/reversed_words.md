
Codewars Python Solutions
---
## Reversed Words <br>
---
Complete the solution so that it reverses all of the words within the string passed in.

Example:

```"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"```

---
### Given code
```python
def reverse_words(s):
    return s
```
---
### Solution
```python
def reverse_words(s):
    l = s.split(' ')
    return ' '.join(list(reversed(l)))
```
