
Codewars Python Solutions
---
## Fake Binary <br>
---
Given a string of digits, you should replace any digit below 5 with '0' and any digit 5 and above with '1'. Return the resulting string.

---
### Given code
```python
def fake_bin(x):
    pass
```
---
### Solution
```python
def fake_bin(x):
    text = ''
    for item in x:
        if int(item) >= 5:
            text += '1'
        elif int(item) < 5:
            text += '0'
    return text
```
