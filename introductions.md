Think of comments as little notes you leave in your code for your future self (because trust me, you'll forget 😭) or for anyone else reading it. They help explain what's going on without affecting the program. 

In Python, anything written after a **`#`** is a comment, which means Python just skips it while running the code. So go ahead—drop reminders, explain tricky parts, or even roast your own code... Python won't judge. 😎


**Example: Single Line Comment**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

**Example: Multiline Comment**

Need to write a comment that's longer than one line? No worries! 😎 You can use triple quotes (''' or """) to write multi-line text.

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```
### Data types

Python has a bunch of different **data types**, and they're basically different ways of storing information. 🧠 Don't stress about memorizing everything right now—we'll dive into each one properly later in the course. For now, just get familiar with the names and what they generally do. Think of this as a quick meet-and-greet before you become besties with them. 😎🚀


#### Number

- Integer: Integer(negative, zero and positive) numbers
    Example:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: Decimal number
    Example
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
    Example
    1 + j, 2 + 4j

#### String

A string is just text in Python. It can be a single character, a word, a sentence, or even a whole paragraph. You can create a string using single quotes (' ') or double quotes (" "). If your text spans multiple lines, use triple quotes (''' ''' or """ """). Think of strings as Python's way of storing anything you can type on your keyboard. 📝✨

**Example:**

```py
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'
```

#### Booleans

A boolean data type is either a True or False value. T and F should be always uppercase.

**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python list is an ordered collection which allows to store different data type items. A list is similar to an array in JavaScript.

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary

A Python dictionary object is an unordered collection of data in a key value pair format.

**Example:**

```py
{
'first_name':'Asabeneh',
'last_name':'Yetayeh',
'country':'Finland',
'age':250,
'is_married':True,
'skills':['JS', 'React', 'Node', 'Python']
}
```

#### Tuple

A tuple is an ordered collection of different data types like list but tuples can not be modified once they are created. They are immutable.

**Example:**

```py
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya') # Names
```

```py
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # planets
```

#### Set

A set is a collection of data types similar to list and tuple. Unlike list and tuple, set is not an ordered collection of items. Like in Mathematics, set in Python stores only unique items.

In later sections, we will go in detail about each and every Python data type.

**Example:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

To check the data type of certain data/variable we use the **type** function.

We use ***type(datatype)*** to check its type

```py
type(2)
type(16.5)
type(false)
type('BloodMaple')
```

### Python File

First open your project folder, 30DaysOfPython. If you don't have this folder, create a folder name called 30DaysOfPython. Inside this folder, create a file called helloworld.py. Now, let's do what we did on python interactive shell using visual studio code.

The Python interactive shell was printing without using **print** but on visual studio code to see our result we should use a built in function _print()_. The _print()_ built-in function takes one or more arguments as follows _print('arument1', 'argument2', 'argument3')_. See the examples below.

**Example:**

The file name is `helloworld.py`

```py
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)             # addition(+)
print(3 - 1)             # subtraction(-)
print(2 * 3)             # multiplication(*)
print(3 / 2)             # division(/)
print(3 ** 2)            # exponential(**)
print(3 % 2)             # modulus(%)
print(3 // 2)            # Floor division operator(//)

# Checking data types
print(type(10))          # Int
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number
print(type('Asabeneh'))  # String
print(type([1, 2, 3]))   # List
print(type({'name':'Asabeneh'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
```



