
Codewars Python Solutions
---
## V A P O R C O D E <br>
---
ASC Week 1 Challenge 4 (Medium #1)

Write a function that converts any sentence into a V A P O R W A V E sentence. a V A P O R W A V E sentence converts all the letters into uppercase, and adds 2 spaces between each letter (or special character) to create this V A P O R W A V E effect.

## Examples
```
"Lets go to the movies"       -->  "L  E  T  S  G  O  T  O  T  H  E  M  O  V  I  E  S"
"Why isn't my code working?"  -->  "W  H  Y  I  S  N  '  T  M  Y  C  O  D  E  W  O  R  K  I  N  G  ?"
```

---
### Given code
```python
def vaporcode(s):
    #your code here
```
---
### Solution
```python
def vaporcode(s):
    s = s.replace(' ', '')
    return '  '.join(s.upper())
```