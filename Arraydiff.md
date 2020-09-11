---
#It should remove all values from list a, which are present in list b.
---

def array_diff(a, b):
   
def array_diff(a, b):
    a=set(a)
    for v in b:
        if v in a:
           a.remove(v)
    return list(a)


