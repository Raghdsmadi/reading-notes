# Reading: Class 09 ((Ten Thousand Game 4))

> [Back to  main](./README.md)
---
## What Are Dunder Methods?
In Python, special methods are a set of predefined methods you can use to enrich your classes. 
They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

- These “dunders” or “special methods” in Python are also sometimes called “magic methods.”


- Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string').
But an empty class definition doesn’t support this behavior out of the box
****************************************************************************************
## Enriching a Simple Account Class
Throughout this article I will enrich a simple Python class with various dunder methods to unlock the following language features:

1- Initialization of new objects
2- Object representation
3- Enable iteration
4- Operator overloading (comparison)
5- Operator overloading (addition)
6- Method invocation
7- Context manager support (with statement)

**************************************************************************************************
### Object Representation: __str__, __repr__
1. __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.

2. __str__: The “informal” or nicely printable string representation of an object. This is for the enduser.

******************************************************************************************************
## Iteration: __len__, __getitem__, __reversed__
In order to iterate over our account object I need to add some transactions. So first, I’ll define a simple method to add transactions. I’ll keep it simple because this is just setup code to explain dunder methods, and not a production-ready accounting system:
- ***Example*** :
```
def add_transaction(self, amount):
    if not isinstance(amount, int):
        raise ValueError('please use int for amount')
    self._transactions.append(amount)
   ```
********************************************************************************************************
## Callable Python Objects: __call__
You can make an object callable like a regular function by adding the __call__ dunder method. 
For our account class we could print a nice report of all the transactions that make up its balance

- ***Example*** :
```
  class Account:
    # ... (see above)

    def __call__(self):
        print('Start amount: {}'.format(self.amount))
        print('Transactions: ')
        for transaction in self:
            print(transaction)
        print('\nBalance: {}'.format(self.balance))

```