
Codewars Python Solutions
---
## Double Char <br>
---
Given a string, you have to return a string in which each character (case-sensitive) is repeated once.
```python
double_char("String") ==> "SSttrriinngg"

double_char("Hello World") ==> "HHeelllloo  WWoorrlldd"

double_char("1234!_ ") ==> "11223344!!__  "
```
Good Luck!

---
### Given code
```python
def double_char(s):
    pass
```
---
### Solution
```python
def double_char(s):
    a = ''
    for item in s:
      a = a + (item*2)
    return a
```
