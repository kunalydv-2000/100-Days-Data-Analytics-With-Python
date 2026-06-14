# Day 03 Notes - Strings & String Operations

## Date

YYYY-MM-DD

---

# What I Learned Today

Today I learned about Strings in Python and various operations that can be performed on textual data.

Strings are one of the most commonly used data types in programming and Data Analytics because datasets often contain text such as:

* Names
* Cities
* Product Categories
* Email Addresses
* Customer Reviews
* Comments

I learned how to create strings, access characters, extract portions of text, and use built-in string methods.

---

# What is a String?

A string is a sequence of characters enclosed in quotation marks.

Examples:

```python
name = "Rahul"
city = "Delhi"
course = "Data Analytics"
```

Strings can contain:

* Letters
* Numbers
* Symbols
* Spaces

---

# Creating Strings

## Double Quotes

```python
language = "Python"
```

## Single Quotes

```python
city = 'Mumbai'
```

## Triple Quotes

Used for multi-line text.

```python
message = """
Welcome
to
Python
"""
```

---

# String Indexing

Each character in a string has a position called an index.

Example:

```python
name = "Python"
```

| Character | P | y | t | h | o | n |
| --------- | - | - | - | - | - | - |
| Index     | 0 | 1 | 2 | 3 | 4 | 5 |

Accessing characters:

```python
print(name[0])
print(name[1])
print(name[5])
```

Output:

```text
P
y
n
```

---

# Negative Indexing

Python allows indexing from the end of a string.

```python
name = "Python"

print(name[-1])
```

Output:

```text
n
```

Useful when the length of the string is unknown.

---

# String Slicing

Slicing extracts a portion of a string.

Syntax:

```python
string[start:end]
```

Example:

```python
name = "DataAnalytics"

print(name[0:4])
```

Output:

```text
Data
```

More examples:

```python
print(name[:4])
print(name[4:])
```

Output:

```text
Data
Analytics
```

---

# String Length

The `len()` function returns the number of characters.

```python
name = "Python"

print(len(name))
```

Output:

```text
6
```

---

# String Methods

Python provides many useful built-in methods.

---

## upper()

Converts text to uppercase.

```python
name = "python"

print(name.upper())
```

Output:

```text
PYTHON
```

---

## lower()

Converts text to lowercase.

```python
name = "PYTHON"

print(name.lower())
```

Output:

```text
python
```

---

## title()

Capitalizes the first letter of every word.

```python
course = "data analytics"

print(course.title())
```

Output:

```text
Data Analytics
```

---

## capitalize()

Capitalizes only the first letter.

```python
city = "delhi"

print(city.capitalize())
```

Output:

```text
Delhi
```

---

## replace()

Replaces text with another value.

```python
sentence = "I like Java"

print(sentence.replace("Java", "Python"))
```

Output:

```text
I like Python
```

---

## strip()

Removes extra spaces.

```python
name = "   Rahul   "

print(name.strip())
```

Output:

```text
Rahul
```

---

# String Concatenation

Combining strings together.

```python
first_name = "Rahul"
last_name = "Sharma"

full_name = first_name + " " + last_name
```

Result:

```text
Rahul Sharma
```

---

# String Repetition

Repeating a string multiple times.

```python
print("Python " * 3)
```

Output:

```text
Python Python Python
```

---

# Membership Operators

Checking whether text exists inside a string.

```python
course = "Data Analytics"

print("Data" in course)
print("Python" in course)
```

Output:

```text
True
False
```

---

# String Formatting

## Using f-Strings

Recommended method for formatting output.

```python
name = "Rahul"
age = 25

print(f"My name is {name}")
print(f"I am {age} years old")
```

Output:

```text
My name is Rahul
I am 25 years old
```

---

# Escape Characters

Special characters used inside strings.

## New Line

```python
print("Python\nData Analytics")
```

Output:

```text
Python
Data Analytics
```

---

## Tab

```python
print("Name\tAge")
```

Output:

```text
Name    Age
```

---

# Useful String Functions

## count()

Counts occurrences of a character.

```python
word = "banana"

print(word.count("a"))
```

Output:

```text
3
```

---

## find()

Returns the position of a character.

```python
word = "Analytics"

print(word.find("t"))
```

Output:

```text
4
```

---

## startswith()

```python
email = "user@gmail.com"

print(email.startswith("user"))
```

Output:

```text
True
```

---

## endswith()

```python
email = "user@gmail.com"

print(email.endswith(".com"))
```

Output:

```text
True
```

---

# Mini Project Notes

## User Profile Formatter

Concepts Used:

* User Input
* String Methods
* String Formatting
* title()

Example:

```python
name = input("Enter your name: ")
city = input("Enter your city: ")

print(f"Name: {name.title()}")
print(f"City: {city.title()}")
```

---

# Common Mistakes

## Index Out of Range

Wrong:

```python
name = "Python"

print(name[10])
```

Error:

```text
IndexError
```

---

## Forgetting Parentheses

Wrong:

```python
name.upper
```

Correct:

```python
name.upper()
```

---

## Case Sensitivity

Wrong:

```python
"python" == "Python"
```

Result:

```text
False
```

Python treats uppercase and lowercase characters differently.

---

# Key Takeaways

1. Strings are sequences of characters.
2. Indexing accesses individual characters.
3. Slicing extracts portions of text.
4. String methods simplify text manipulation.
5. f-strings provide clean formatting.
6. Text processing is essential for Data Analytics.
7. Understanding strings helps with data cleaning tasks later in Pandas.

---

# Reflection

### What I Practiced

* String creation
* Indexing
* Slicing
* String methods
* String formatting
* User input

### What I Need More Practice On

* Complex slicing
* Combining multiple string methods
* Real-world text cleaning

---

# Tomorrow's Goal

## Day 04 - Lists & List Operations

Topics:

* Creating Lists
* List Indexing
* List Slicing
* List Methods
* Nested Lists
* Mini Project

Lists are one of the most important data structures for storing collections of data in Python.
