
Codewars Python Solutions
---
## Century From Year <br>
---
Introduction
The first century spans from the year 1 up to and including the year 100, the second century - from the year 101 up to and including the year 200, etc.

Task
Given a year, return the century it is in.

Examples
```
1705 --> 18
1900 --> 19
1601 --> 17
2000 --> 20
```
---
### Given code
```python
def century(year):
    # Finish this :)
    return
```
---
### Solution
```python
import math
def century(year):
    century = year / 100
    if isinstance(century, float):
        century = math.ceil(century)
    return century
```

### Solution 2
```python
import math
def century(year):
    return math.ceil(year / 100)
```
