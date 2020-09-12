---
#This code takes a string and return a new string with all vowels removed.
---

*Code wars version*

```
def disemvowel(string):
    string = string.replace("a","")
    string = string.replace("e","")
    string = string.replace("u","")
    string = string.replace("i","")
    string = string.replace("o","")
    string = string.replace("O","")
    string = string.replace("U","")
    string = string.replace("I","")
    string = string.replace("E","")
    string = string.replace("A","")
    return string
```

*Python 3.5.8 Shell*

```
def disemvowel(s):
    for i in "aeiouAEIOU":
        s = s.replace(i,'')
    return s

test = ["Remove the vowels",
         "Rmv th vwls"
         ]

assert disemvowel(test[0])==test[1]
```
