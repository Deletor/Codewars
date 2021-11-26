
Codewars Python Solutions
---
## Sort and Star <br>
---
You will be given a vector of strings. You must sort it alphabetically (case-sensitive, and based on the ASCII values of the chars) and then return the first value.

The returned value must be a string, and have ```***``` between each of its letters.

You should not remove or add elements from/to the array.

---
### Given code
```python
def two_sort(array):
    # your code here
```
---
### Solution
```python
def two_sort(array):
    list = sorted(array)
    a = ''
    num = len(list[0])
    n = 0
    for i in list[0]:
        a += i
        if n < num-1:
            n += 1
            a += '***'
    return a
```
