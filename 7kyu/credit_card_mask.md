
Codewars Python Solutions
---
## Credit Card Mask <br>
---
Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it.

Your task is to write a function maskify, which changes all but the last four characters into '#'.
```
Examples
maskify("4556364607935616") == "############5616"
maskify(     "64607935616") ==      "#######5616"
maskify(               "1") ==                "1"
maskify(                "") ==                 ""

# "What was the name of your first pet?"
maskify("Skippy")                                   == "##ippy"
maskify("Nananananananananananananananana Batman!") == "####################################man!"
```
---
### Given code
```python
# return masked string
def maskify(cc):

    pass
```
---
### Solution
```python
# return masked string
def maskify(cc):
    str = ''
    for char in cc[:-4]:
        str += '#'
    str += cc[-4:]
    return str
```
