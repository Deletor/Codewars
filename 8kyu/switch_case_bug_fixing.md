
Codewars Python Solutions
---
## Switch/Case - Bug Fixing #6 <br>
---
Oh no! Timmy's evalObject function doesn't work. He uses Switch/Cases to evaluate the given properties of an object, can you fix timmy's function?

---
### Given code
```python
def eval_object(v):
    return {"+": v['a']+v['b'],
        "-": v['a']-v['b'],
        "/": v['a']/v['b'],
        "*": v['a']*v['b'],
        "%": v['a']%v['b'],
        "**": v['a']**v['b'], }.get('operation',1)
```
---
### Solution
```python
def eval_object(v):
  return {
      "+": v['a'] + v['b'],
      "-": v['a']-v['b'],
      "/": v['a']/v['b'],
      "*": v['a']*v['b'],
      "%": v['a']%v['b'],
      "**": v['a']**v['b'], }.get(v['operation'])
```
