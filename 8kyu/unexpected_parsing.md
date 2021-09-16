
Codewars Python Solutions
---
## Unexpected parsing <br>
---
Here is a piece of code:
```python
def get_status(is_busy):
    status = "busy" if is_busy else "available"
    return status
```
**Expected Behaviour**
Function should return a dictionary/Object/Hash with ```"status"``` as a key, whose value can : ```"busy"``` or ```"available"``` depending on the truth value of the argument ```is_busy```.

But as you will see after clicking ```RUN``` or ```ATTEMPT``` this code has several bugs, please fix them.

---
### Given code
```python
def get_status(is_busy):
    status = "busy" if is_busy else "available"
    return status
```
---
### Solution
```python
def get_status(is_busy):
    return {"status": ("available", "busy")[is_busy]}
```
