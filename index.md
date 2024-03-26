# This is a `<h1>` header
## This is a `<h2>` header
### This is a `<h3>` header
#### This is a `<h4>` header
##### This is a `<h5>` header
###### This is a `<h6>` header

# This is ***a new image*** for this file
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

# This is a **Python code** calculate total wage
``` python
Hours = int(input('Enter hours:'))
hourlyRate = float(input('Enter rate:'))

if Hours > 40:
    Normalhours = 40
    overTimeHours = Hours - 40
    pay = (Normalhours * hourlyRate) +  (overTimeHours) * (hourlyRate * 1.5)
else:
    pay = Hours * hourlyRate
    
print("Pay:",pay)
```
