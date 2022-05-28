> [Back to  main](../README.md)
### Reading Class01 :
### Big O :
The reference : [Big O](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation)
<br>

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm. Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.
<br>

Types of Big O Notation : <br>

- O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.
<br>

- O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. The example below also demonstrates how Big O favours the worst-case performance scenario; a matching string could be found during any iteration of the for loop and the function would return early, but Big O notation will always assume the upper limit where the algorithm will perform the maximum number of iterations.
<br>

- O(N²)
O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set. This is common with algorithms that involve nested iterations over the data set. Deeper nested iterations will result in O(N³), O(N⁴) etc.
 <br>

- O(2^N)
O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set. The growth curve of an O(2^N) function is exponential — starting off very shallow, then rising meteorically. An example of an O(2^N) function is the recursive calculation of Fibonacci numbers:

### Logarithms : 
In mathematics, the logarithm is the inverse function to exponentiation. That means the logarithm of a given number x is the exponent to which another fixed number, the base b, must be raised, to produce that number x.
<br>

## Python Environment

- Python
  - it is an interpreted language
  - when we assign a value to any type of variables, it will be assigned to the reference value not the value itself. which means if we changed the reference value of the variable, the value of the variable will be changed too.

    ---

- Python data types
  - Text Type:
    - str: strings
  - Numeric Types:
    - int: integers
    - float: floats
    - complex: complex (imaginary numbers)
  - Sequence Types:
    - list
    - tuple
    - range
  - Mapping Type:
    - dict: dictionaries
  - Set Types:
    - set
    - frozenset
  - Boolean Type:
    - bool: Boolean
  - Binary Types:
    - bytes
    - bytearray
    - memoryview

---
