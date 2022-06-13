# Reading: Class 07 ((Ten Thousand Game 2))

> [Back to  main](./README.md)
---

## Creating Python Inner Functions
A function defined inside another function is known as an inner function or a nested function. 
In Python, this kind of function can access names in the enclosing function.
- ***Example***
```
 def outer_func():
       def inner_func():
         print("Hello, World!")
          inner_func()


 outer_func()
```

*************************************************************
## Providing Encapsulation
A common use case of inner functions arises when you need to protect, or hide, a given function from everything happening outside of it so that the function is totally hidden from the global scope. 
This kind of behavior is commonly known as encapsulation.


## Building Helper Inner Functions
Sometimes you have a function that performs the same chunk of code in several places within its body.


## Retaining State in a Closure
A closure causes the inner function to retain the state of its environment when called. The closure isn’t the inner function itself but the inner function along with its enclosing environment. 
The closure captures the local variables and name in the containing function and keeps them around.
 - ***Example:***
```

def generate_power(exponent):
    def power(base):
        return base ** exponent
    return power
```

## Modifying the Closure State
Normally, closure variables are completely hidden from the outside world. However, you can provide getter and setter inner functions for them

## Adding Behavior With Inner Functions: Decorators
Python decorators are another popular and convenient use case for inner functions, especially for closures.
Decorators are higher-order functions that take a callable (function, method, class) as an argument and return another callable.

- ***Example*** 
```
@decorator
def decorated_func():
    # Function body...
    pass
```