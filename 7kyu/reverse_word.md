
Codewars Python Solutions
---
## Reverse word <br>
---
Complete the function that accepts a string parameter, and reverses each word in the string. **All** spaces in the string should be retained.

**Examples**
```
"This is an example!" ==> "sihT si na !elpmaxe"
"double  spaces"      ==> "elbuod  secaps"
```
---
### Given code
```python
def reverse_words(text):
  #go for it
```
---
### Solution
```python
def reverse_words(text):
    return ' '.join(i[::-1] for i in text.split(' '))
```
