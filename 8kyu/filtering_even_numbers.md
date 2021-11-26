
Codewars Python Solutions
---
## Fix the bug in Filtering method <br>
---
The method is supposed to remove even numbers from the list and return a list that contains the odd numbers.

However, there is a bug in the method that needs to be resolved.

---
### Given code
```python
def kata_13_december(lst): 
    # Fix this code
    for i in range(len(lst)): 
        if lst[i]%2==0: 
            lst.remove(i)
    return lst
```
---
### Solution
```python
def kata_13_december(lst): 
    # Fix this code
    arr = []
    for i in range(len(lst)): 
        if lst[i] % 2 == 0:
            pass
        else:
            arr.append(lst[i])
    return arr
```
