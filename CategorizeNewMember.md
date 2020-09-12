---
#To be a senior, a member must be at least 55 years old (index 0) and have a handicap (index 1) greater than 7. 
---


```
import re
def open_or_senior(data):

    result = ""

    if (data[0][0]>=55 & data[0][1]>7):
        result+="Senior"
    
    else:
        result+="Open"

    if (data[1][0]>=55 & data[1][1]>7):
        result+="Senior"
    
    else:
        result+="Open"

    if (data[2][0]>=55 & data[2][1]>7):
        result+="Senior"
    
    else:
        result+="Open"

    if (data[3][0]>=55 & data[3][1]>7):
        result+="Senior"
    
    else:
        result+="Open"

    return result

data =[[18, 20],[45, 2],[61, 12],[37, 6]]

print(re.sub( r"([A-Z])", r" \1", open_or_senior(data)).split())
```
   
