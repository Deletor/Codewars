
Codewars Python Solutions
---
## Remove duplicate words <br>
---
Your task is to remove all duplicate words from a string, leaving only single (first) words entries.

**Example:**

Input:

'alpha beta beta gamma gamma gamma delta alpha beta beta gamma gamma gamma delta'

Output:

'alpha beta gamma delta'

---
### Given code
```python
def remove_duplicate_words(s):
    #pass
```
---
### Solution
```python
def remove_duplicate_words(s):
    return " ".join(sorted(set(s.split()), key = s.index))
```
