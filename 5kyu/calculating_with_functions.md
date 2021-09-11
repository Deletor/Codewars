
Codewars Python Solutions
---
## Calculating with Functions<br>
---
This time we want to write calculations using functions and get the results. Let's have a look at some examples:
```python
seven(times(five())) # must return 35
four(plus(nine())) # must return 13
eight(minus(three())) # must return 5
six(divided_by(two())) # must return 3
```
Requirements:

- There must be a function for each number from 0 ("zero") to 9 ("nine")
- There must be a function for each of the following mathematical operations: plus, minus, times, dividedBy (```divided_by``` in Ruby and Python)
- Each calculation consist of exactly one operation and two numbers
- The most outer function represents the left operand, the most inner function represents the right operand
- Division should be integer division. For example, this should return ```2```, not ```2.666666...```:
```
eight(divided_by(three()))
```
---
### Given code
```python
def zero(): #your code here
def one(): #your code here
def two(): #your code here
def three(): #your code here
def four(): #your code here
def five(): #your code here
def six(): #your code here
def seven(): #your code here
def eight(): #your code here
def nine(): #your code here

def plus(): #your code here
def minus(): #your code here
def times(): #your code here
def divided_by(): #your code here
```
---
### Solution
```python
def zero(f = None): return 0 if f is None else int(f(0))
def one(f = None): return 1 if f is None else int(f(1))
def two(f = None): return 2 if f is None else int(f(2))
def three(f = None): return 3 if f is None else int(f(3))
def four(f = None): return 4 if f is None else int(f(4))
def five(f = None): return 5 if f is None else int(f(5))
def six(f = None): return 6 if f is None else int(f(6))
def seven(f = None): return 7 if f is None else int(f(7))
def eight(f = None): return 8 if f is None else int(f(8))
def nine(f = None): return 9 if f is None else int(f(9))

def plus(y): return lambda x: x + y
def minus(y): return lambda x: x - y
def times(y): return lambda x: x * y
def divided_by(y): return lambda x: x / y
```
