
Codewars Python Solutions
---
## Is it a number? <br>
---
Given a string s, write a method (function) that will return true if its a valid single integer or floating number or false if its not.

Valid examples, should return true:

```python
isDigit("3")
isDigit("  3  ")
isDigit("-3.23")
should return false:
```
```python
isDigit("3-4")
isDigit("  3   5")
isDigit("3 5")
isDigit("zero")
```

---
### Given code
```python
def isDigit(string):
    #11ELF
```
---
### Solution
```python
def isDigit(string):
    try:
        float(string)
        return True
    except:
        return False
```
