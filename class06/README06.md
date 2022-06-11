# Reading: Class 06 ((Ten Thousand Game 1))

> [Back to  main](./README.md)
---
## How to use the Random Module in Python
The random module provides access to functions that support many operations.
Perhaps the most important thing is that it allows you to generate random numbers.

*****************************************************************************
### Random functions

- **Randint** <br>
If we wanted a random integer, we can use the randint function Randint accepts two parameters: a lowest and a highest number.

**Example** :
```import random 
print random.randint(0, 5)
This will output either 1, 2, 3, 4 or 5.
```

- **Random** <br>
If you want a larger number, you can multiply it.
**Example** :
```
import random
random.random() * 100
```
- **Choice** <br>
Generate a random value from the sequence sequence.

The choice function can often be used for choosing a random element from a list.
**Example** :
```
import random
myList = [2, 109, False, 10, "Lorem", 482, "Ipsum"]
random.choice(myList)
```

- **Shuffle** <br>
The shuffle function, shuffles the elements in list in place, so they are in a random order.

**Example** :
```
from random import shuffle
x = [[i] for i in range(10)]
shuffle(x)
```

- **Randrange** <br>
Generate a randomly selected element from range(start, stop, step)

 ***random.randrange(start, stop[, step])*** <br>
**Example** :
```
import random
for i in range(3):
    print random.randrange(0, 101, 5)
```
*******************************************************************
## Why use Risk Analysis?
t helps the developers and managers to mitigate the risks.
When a test plan has been created, risks involved in testing the product are to be taken into consideration along with the possibility of the damage they may cause to your software along with solutions.
<br>
## What are these risk magnitude indicators?
High: means the effect of the risk would be very high and non-tolerable. The company might face loss.

Medium: it is tolerable but not desirable. The company may suffer financially but there is a limited risk.

Low: it is tolerable. There lies little or no external exposure or no financial loss.

## Risk Identification
There are different sets of risks included in the risk identification process. Those are as follows:
1. Business Risks
2. Testing Risks
3. Premature Release Risk
4. Software Risks

### The perspective of Risk Assessment :
**There are three perspectives of Risk Assessment:**

1. Effect – To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.

2. Cause – To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.

3. Likelihood – To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.


### How to perform Risk Analysis?
***There are three steps:***

- Searching the risk

- Analyzing the impact of each individual risk

- Measures for the risk identified