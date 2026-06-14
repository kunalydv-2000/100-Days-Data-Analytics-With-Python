# Day 02 Notes - Data Types & Type Conversion

## Date

2026-06-13

---

# What I Learned Today

Today I learned how Python stores different types of data and how to convert data between various data types.

I also learned how user input works in Python and why type conversion is necessary when performing calculations.

---

# Python Data Types

A data type defines the kind of value stored in a variable.

---

## String (str)

Used to store text.

```python
name = "Rahul"
city = "Delhi"
```

Characteristics:

* Enclosed in quotes
* Can contain letters, numbers, and symbols
* Immutable

Example:

```python
print(name.upper())
print(name.lower())
```

---

## Integer (int)

Used for whole numbers.

```python
age = 25
year = 2025
```

Examples:

```python
10
50
-100
```

---

## Float (float)

Used for decimal numbers.

```python
height = 5.8
price = 99.99
```

Examples:

```python
3.14
5.75
100.0
```

---

## Boolean (bool)

Represents True or False values.

```python
is_student = True
is_admin = False
```

Commonly used in conditions and comparisons.

Example:

```python
age = 18

print(age >= 18)
```

Output:

```text
True
```

---

# type() Function

Used to check data types.

```python
print(type("Python"))
print(type(100))
print(type(99.99))
print(type(True))
```

Output:

```text
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```

---

# Type Conversion

Type conversion means changing one data type into another.

---

## int()

Converts values into integers.

```python
age = int("25")
```

---

## float()

Converts values into floats.

```python
price = float("99.99")
```

---

## str()

Converts values into strings.

```python
score = str(100)
```

---

## bool()

Converts values into boolean values.

```python
bool(1)
bool(0)
```

Results:

```text
True
False
```

---

# User Input

Input is always stored as a string.

Example:

```python
age = input("Enter age: ")
```

Even if the user enters:

```text
25
```

Python stores it as:

```python
"25"
```

---

# Why Type Conversion is Needed

Wrong:

```python
age = input("Enter age: ")

print(age + 10)
```

Produces an error.

Correct:

```python
age = int(input("Enter age: "))

print(age + 10)
```

---

# Mini Project Notes

Created an Age Calculator.

Concepts Used:

* Variables
* Input
* Integer Conversion
* Arithmetic Operations
* f-Strings

---

# Common Errors

## Forgetting Conversion

Wrong:

```python
age = input()
print(age + 10)
```

Correct:

```python
age = int(input())
print(age + 10)
```

---

## Invalid Integer Conversion

Wrong:

```python
int("hello")
```

Produces:

```text
ValueError
```

---

# Key Takeaways

1. Everything in Python has a data type.
2. Strings store text.
3. Integers store whole numbers.
4. Floats store decimal values.
5. Booleans store True/False values.
6. User input is always a string.
7. Type conversion is essential when working with user input.
8. Data types are the foundation of data analysis.

---

# Questions for Further Learning

* How does Python store data internally?
* What are mutable and immutable data types?
* What are lists and dictionaries?

---

# Tomorrow's Goal

### Day 03 - Strings & String Operations

Topics:

* String Indexing
* String Slicing
* String Methods
* String Formatting
* Practice Problems
* Mini Project
