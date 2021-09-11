
Codewars Python Solutions
---
## Total amount of points <br>
---
Our football team finished the championship. The result of each match look like "x:y". Results of all matches are recorded in the collection.

For example: ```["3:1", "2:2", "0:1", ...]```

Write a function that takes such collection and counts the points of our team in the championship. Rules for counting points for each match:

- if x>y - 3 points
- if x<y - 0 point
- if x=y - 1 point
Notes:

there are 10 matches in the championship
0 <= x <= 4
0 <= y <= 4

---
### Given code
```python
def points(games):
	pass
```
---
### Solution
```python
def points(games):
    s = 0
    for item in games:
        x = item[0]
        y = item[2]
        if x > y: s += 3
        elif x < y: pass
        elif x == y: s += 1
    return s
```
