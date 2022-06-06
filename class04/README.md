# Reading: Class 04

> [Back to the main](./README.md)
---

## Defining a class:

    class MyClass:
        pass

---

## Instances of the class:

    objectt = MyClass() 

defines an object (instance) of the class

    isinstance(var1, class1) 

it will return (True) if the variable (var1) is differentiated from the class (class1). Otherwise, it will print (False)

    del obj1

that will delete the object  

---

## Class constructor:

it is the main function inside the class that will be run automatically every time we define an instance of the class

it is defined by default without parameters in any class:

    class MyClass:
        def __init__(self)
            pass

we can add parameters to the class:

    class MyClass:
        def __init__(self, par1, par2)
            pass

and we have to fill the arguments in the instance we define:

    MyClass(1,2)

---
## Class inheritance

### The child class: 

we can define a class that inherits all the attributes and methods of the parent class (it is like we define the same attributes and methods in the new class with the same values, names, types, scopes and parameters)
 

## init()
The __init__() function, is a special function that is called when the class is being initiated. It's used for asigning values in a class.

## Dictionaries
A dictionary is a data type similar to arrays, but works with keys and values instead of indexes. Each value stored in a dictionary can be accessed using a key, which is any type of object (a string, a number, a list, etc.) instead of using its index to address it.

## Accessing Object Functions
To access a function inside of an object you use notation similar to accessing a variable

## Recursive Data Structures in Python
A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure. Let me demonstrate. Assume that you have only an empty list at your disposal, and the only operation you can perform on it is this