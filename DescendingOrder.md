---
#This orders a nums digits in descending order.
---

```
def descending_order(num):
    digits = [int(i) for i in str(num)]
    digits.sort(reverse=True)
    #print(digits)
    #print(sorted_num,num)
    result = ""
    for i in digits:
        result+=str(i)
    return int(result)

print (descending_order(374982))
```
