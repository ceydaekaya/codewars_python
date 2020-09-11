---
#It should remove all values from list a, which are present in list b.
---

def array_diff(a, b):
    
    result = []
    i = 0;
    j = 0;
    
    if (a[i] == b[j]):
            a = a.remove(a[i]) #append() method in python adds a single item to the existing list
            
            if i<len(a):
                i+=1;
            return a;
            if j<len(b):
                i+=1;
            else return a;


