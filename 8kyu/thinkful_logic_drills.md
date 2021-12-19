
Codewars Python Solutions
---
## Thinkful - Logic Drills: Traffic light <br>
---
You're writing code to control your town's traffic lights. You need a function to handle each change from ```green```, to ```yellow```, to ```red```, and then to ```green``` again.

Complete the function that takes a string as an argument representing the current state of the light and returns a string representing the state the light should change to.

For example, ```update_light('green')``` should return ```'yellow'```.

Note: Use ```""``` instead of ```''``` in C++.

---
### Given code
```python
def update_light(current):
    # Your code here.
```
---
### Solution
```python
def update_light(current):
    if current == 'green':
        return 'yellow'
    elif current == 'yellow':
        return 'red'
    else:
        return 'green'
```