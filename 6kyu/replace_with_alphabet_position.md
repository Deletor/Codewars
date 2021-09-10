
Codewars Python Solutions
---
## Replace With Alphabet Position <br>
---
Welcome.
<br>
In this kata you are required to, given a string, replace every letter with its position in the alphabet.
<br>
If anything in the text isn't a letter, ignore it and don't return it.

```a" = 1```, ```"b" = 2```, etc.

**Example**
```python
alphabet_position("The sunset sets at twelve o' clock.")
```
Should return ```"20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11"``` (as a string)

---
### Given code
```python
def alphabet_position(text):
    pass
```
---
### Solution
```python
def alphabet_position(text):
    end = ''
    for x in text.lower():
        if x >= 'a' and x <= 'z':
            nums = str(ord(x) - 96)
            end = end + nums + ' '
    return end[:-1]
```
