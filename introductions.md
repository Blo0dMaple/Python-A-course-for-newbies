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

A **Boolean** is the simplest data type in Python—it can only have **two values: `True` or `False`**. Think of it like an **ON/OFF switch** or answering a **Yes/No** question. One important thing to remember: **`True` and `False` always start with a capital letter**. If you write `true` or `false` in lowercase, Python won't be happy. 😅


**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

A **list** is like Python's backpack 🎒—you can throw in almost anything! It stores items in a specific order, and those items can be of **different data types** like numbers, text, or even other lists. Unlike some languages, Python doesn't care if the items are all different. If you've used JavaScript before, a Python list is pretty similar to a JavaScript array. 😎


**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary
A **dictionary** stores data as **key-value pairs**, kind of like a real dictionary where each **word (key)** has a **meaning (value)**. 🔑 Instead of using numbers to find items like a list, you use unique keys to access their values. It's one of the most useful data types in Python for organizing and looking up information quickly. 🚀


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

A **tuple** is a lot like a **list**—it can store multiple items in a specific order, and those items can be of different data types. The big difference? **Once you create a tuple, you can't change it.** 🚫 That means you can't add, remove, or update its items. In Python terms, tuples are **immutable**, making them perfect for storing data that should stay the same.


**Example:**

```py
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya') # Names
```

```py
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # planets
```

#### Set

A **set** is another way to store multiple items in Python, but it has two special rules: **it's unordered** and **it only keeps unique values**. 🎯 That means duplicate items are automatically removed, and the order of the items isn't guaranteed. You can think of it like a collection where every item gets only one VIP entry. 😎

Don't worry if all these data types seem a bit confusing right now—we'll explore each one in detail later in the course with plenty of examples and fun coding practice. By the end, you'll know exactly when and why to use each one. 🚀

**Example:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

Want to know what type of data you're working with? 🤔 Just use Python's built-in **`type()`** function. It tells you whether a value or variable is an **integer, float, string, list, dictionary**, or any other data type. It's one of the handiest functions for beginners and super useful when you're debugging or just curious about your code. 🔍🚀


We use ***type(datatype)*** to check its type

```py
type(2)
type(16.5)
type('BloodMaple')
```

### Python File
Let's write your very first Python program! 🎉

First, open your project folder called **`30DaysOfPython`**. If you don't have one yet, create it. Inside that folder, create a new file named **`helloworld.py`**.

Now it's time to code! 😎

Unlike the **Python Interactive Shell**, where you can simply type a value and see the output, in a Python file you need to use the built-in **`print()`** function to display anything on the screen.

The `print()` function can display one or more values. Its basic syntax looks like this:

```py
print("argument1")
print("argument1", "argument2", "argument3")
```

Go ahead and try a few examples below. Run your program and watch your first Python output appear on the screen. Congrats—you've officially started coding! 🚀


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



