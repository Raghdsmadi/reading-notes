# Reading: Class 07 ((Ten Thousand Game 2))

> [Back to  main](./README.md)
---

## List Comprehensions in Python

List comprehension is a powerful and concise method for creating lists in Python that becomes essential the more you work with lists, and lists of lists.
- ***Syntax***
```
my_new_list = [ expression for item in list ]
```

### importance of Comprehensions in Python :
- List comprehension methods are an elegant way to create and manage lists. 
- In Python, list comprehensions are a more compact way of creating lists. 
- More flexible than for loops, list comprehension is usually faster than other methods.

*************************************************************
## Create a List with range()
- ***Example 1*** :
```
digits = [x for x in range(10)]

print(digits)
```
```
Output

[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```
******************************************************************
### create a list using a for loop

- ***Example 2*** :
```
squares = []

for x in range(10):
    # raise x to the power of 2
    squares.append(x**2)

print(squares)
```
```
Output
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

```
**************************************************************
### Multiplying Parts of a List

- ***Example 3: Multiplication with list comprehensions*** :

```
multiples_of_three = [ x*3 for x in range(10) ]

print(multiples_of_three)
```

```
Output

[0, 3, 6, 9, 12, 15, 18, 21, 24, 27]
```
*******************************************************************
### Show the first letter of each word using Python
So far we’ve seen examples of building a list of numbers in Python. Next, let’s try working with strings and the various ways list comprehensions can be used to elegantly handle a list of strings.
- ***Example 4: Using list comprehensions with strings*** :
```
# a list of the names of popular authors
authors = ["Ernest Hemingway","Langston Hughes","Frank Herbert","Toni Morrison",
    "Emily Dickson","Stephen King"]

# create an acronym from the first letter of the author's names
letters = [ name[0] for name in authors ]
print(letters)
```
```
Output

['E', 'L', 'F', 'T', 'E', 'S']
```

***********************************************************************************
### Lower/Upper case converter using Python :
Using list comprehension to loop through a string in Python, it’s possible to convert strings from lower case to upper case, and vice versa. 

- ***Example 5: Changing a letter’s case***

```
lower_case = [ letter.lower() for letter in ['A','B','C'] ]
upper_case = [ letter.upper() for letter in ['a','b','c'] ]

print(lower_case, upper_case)
```
```
Output

['a', 'b', 'c'] ['A', 'B', 'C']
```

********************************************************************************************

### Parsing a file using list comprehension
It’s also possible to read files in Python using list comprehension. To demonstrate, I’ve created a file called dreams.txt and pasted the following text, a short poem by Langston Hughes.
Using list comprehension, we can iterate through the lines of text in the file and store their contents in a new list

- ***Example 8: Reading a poem with list comprehensions*** :
```
# open the file in read-only mode
file = open("dreams.txt", 'r')
poem = [ line for line in file ]

for line in poem:
    print(line)
```
```
Output

Hold fast to dreams
For if dreams die

Life is a broken-winged bird

That cannot fly.

-Langston Hughs
```