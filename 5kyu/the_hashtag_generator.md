
Codewars Python Solutions
---
## Multiples of 3 or 5 <br>
---
The marketing team is spending way too much time typing in hashtags.
Let's help them with our own Hashtag Generator!

Here's the deal:

- It must start with a hashtag (```#```).
- All words must have their first letter capitalized.
- If the final result is longer than 140 chars it must return ```false```.
- If the input or the result is an empty string it must return ```false```.
**Examples**
```
" Hello there thanks for trying my Kata"  =>  "#HelloThereThanksForTryingMyKata"
"    Hello     World   "                  =>  "#HelloWorld"
""                                        =>  false
```
---
### Given code
```python
def generate_hashtag(s):
    #your code here
```
---
### Solution
```python
def generate_hashtag(s):
    long = len(s)
    t = ''
    if s == '' or long >= 140:
        return False
    else:
        spl = s.split(' ')
        for item in spl:
            t += item.capitalize()
        return '#'+ t
```
