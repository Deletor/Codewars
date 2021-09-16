
Codewars Python Solutions
---
## Regex count lowercase letters <br>
---

Your task is simply to count the total number of lowercase letters in a string.

**Examples**
```python
lowercaseCount("abc"); ===> 3

lowercaseCount("abcABC123"); ===> 3

lowercaseCount("abcABC123!@€£#$%^&*()_-+=}{[]|\':;?/>.<,~"); ===> 3

lowercaseCount(""); ===> 0;

lowercaseCount("ABC123!@€£#$%^&*()_-+=}{[]|\':;?/>.<,~"); ===> 0

lowercaseCount("abcdefghijklmnopqrstuvwxyz"); ===> 26
```
---
### Given code
```python
def lowercase_count(strng):
    # Your code here
```
---
### Solution
```python
def lowercase_count(strng):
    sum = 0
    for i in strng:
        if i.islower(): sum +=1
    return sum
```
