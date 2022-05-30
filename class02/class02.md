# Reading: Class 02

> [Back to the main](../README.md)
## TDD (Test-Driven Development)

- Test Driven Development (TDD) is software development approach in which test cases are developed to specify and validate what the code will do. In simple terms, test cases for each functionality are created and tested first and if the test fails then the new code is written in order to pass the test and making code simple and bug-free.

- We create multiple test units using the **assert** keyword, which assert that the given expression is True to complete the program. It raise an error otherwise.

- ***"This means both parties in the pair are engaged, focused on what they are doing, and checking one another's work at every stage."***

## Script or Module

- The following is used to execute some code only if the file was run directly, and not imported

```
if __name__ == "__main__":
    print("this file is run by itself")
else:
    print("this file is run by another")
```

---

## Recursion 

- it is a programming feature allow us to call the function from its body to solve a complex problem and save time 
```
def recur_fibo(n):
   if n <= 1:
       return n
   else:
       return(recur_fibo(n-1) + recur_fibo(n-2))

nterms = 10

if nterms <= 0:
   print("Plese enter a positive integer")
else:
   print("Fibonacci sequence:")
   for i in range(nterms):
       print(recur_fibo(i))


```