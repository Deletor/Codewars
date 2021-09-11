
Codewars Python Solutions
---
## Grasshopper - Terminal game combat function <br>
---
Create a combat function that takes the player's current health and the amount of damage recieved, and returns the player's new health. Health can't be less than **0**.

---
### Given code
```python
def combat(health, damage):
    #your code here
```
---
### Solution
```python
def combat(health, damage):
    life = health - damage
    if life >= 0:
        return life
    else: return 0
```
