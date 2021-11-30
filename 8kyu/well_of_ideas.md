
Codewars Python Solutions
---
## Well of Ideas - Easy Version <br>
---
For every good kata idea there seem to be quite a few bad ones!

In this kata you need to check the provided array (x) for good ideas 'good' and bad ideas 'bad'. If there are one or two good ideas, return 'Publish!', if there are more than 2 return 'I smell a series!'. If there are no good ideas, as is often the case, return 'Fail!'.

---
### Given code
```python
def well(x):
    #your code here
    return ''
```
---
### Solution
```python
def well(x):
    sum = x.count('good')
    if sum == 1 or sum == 2:
        return 'Publish!'
    elif sum > 2:
        return 'I smell a series!'
    else: return 'Fail!'
```
