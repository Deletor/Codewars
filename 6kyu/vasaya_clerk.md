
Codewars Python Solutions
---
## Vasya - Clerk <br>
---
The new "Avengers" movie has just been released! There are a lot of people at the cinema box office standing in a huge line. Each of them has a single ```100```, ```50``` or ```25``` dollar bill. An "Avengers" ticket costs ```25 dollars```.

Vasya is currently working as a clerk. He wants to sell a ticket to every single person in this line.

Can Vasya sell a ticket to every person and give change if he initially has no money and sells the tickets strictly in the order people queue?

Return ```YES```, if Vasya can sell a ticket to every person and give change with the bills he has at hand at that moment. Otherwise return ```NO```.

**Examples:**
```
tickets([25, 25, 50]) # => YES 
tickets([25, 100]) # => NO. Vasya will not have enough money to give change to 100 dollars
tickets([25, 25, 50, 50, 100]) # => NO. Vasya will not have the right bills to give 75 dollars of change (you can't make two bills of 25 from one of 50)
```


---
### Given code
```python
def tickets(people):
    return "?"
```
---
### Solution
```python
def tickets(people):
    cash = {
    25: 0,
    50: 0,
    100: 0
    }
    for item in people:
        if (item == 25):
            cash[item] += 1
        else:
            cash[item] += 1

            if (item == 50 and cash[25] < 1): return 'NO'
            elif (item == 50): cash[25] -= 1

            if (item == 100 and ((cash[25] < 1 and cash[50] < 50) or cash[25] < 3)): return 'NO'
            elif (item == 100):
                if (cash[50] > 0 and cash[25] > 1):
                    cash[25] -= 1
                    cash[50] -= 1
                elif (cash[25] >= 3):
                    cash[25] -= 3
    return 'YES'
```
