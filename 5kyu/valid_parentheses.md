
Codewars Python Solutions
---
## Valid parentheses <br>
---
Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid. The function should return ```true``` if the string is valid, and ```false``` if it's invalid.

**Examples**
```
"()"              =>  true
")(()))"          =>  false
"("               =>  false
"(())((()())())"  =>  true
```
**Constraints**
```
0 <= input.length <= 100
```
Along with opening (```(```) and closing (```)```) parenthesis, input may contain any valid ASCII characters. Furthermore, the input string may be empty and/or not contain any parentheses at all. Do not treat other forms of brackets as parentheses (e.g. ```[]```, ```{}```, ```<>```).

---
### Given code
```python
def valid_parentheses(string):
    #your code here
```
---
### Solution
```python
def valid_parentheses(string):
    #your code here
    arr = []
    for s in string:
        if s == '(':
            arr.append(s)
        elif s == ')':
            try:
                arr.pop()
            except:
                return False

    if (len(arr) == 0):
        return True
    else:
        return False
```