
Codewars Python Solutions
---
## Name Shuffler <br>
---
Write a function that returns a string in which firstname is swapped with last name.
```python
name_shuffler('john McClane'); => "McClane john"
```

---
### Given code
```python
def name_shuffler(str_):
    #your code here
```
---
### Solution
```python
def name_shuffler(str_):
    return ' '.join(str_.split(' ')[::-1])
```
