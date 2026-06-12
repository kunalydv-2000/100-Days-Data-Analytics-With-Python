# Day 01 Notes - Python Setup & Variables

## Date

YYYY-MM-DD

---

# What I Learned Today

Today I set up my Python development environment and learned how variables work in Python.

I installed:

* Python
* VS Code
* Python Extension
* Jupyter Notebook

I also created and executed my first Python program.

---

# First Python Program

```python
print("Hello Data Analytics!")
print("Welcome to Day 1")
```

Output:

```text
Hello Data Analytics!
Welcome to Day 1
```

---

# What is Python?

Python is a high-level, interpreted programming language known for:

* Simple syntax
* Easy readability
* Large ecosystem
* Strong support for Data Analytics and Data Science

Python is widely used for:

* Data Analytics
* Data Science
* Machine Learning
* Web Development
* Automation

---

# What is a Variable?

A variable is a named container used to store data.

Example:

```python
name = "Rahul"
age = 25
```

Here:

```text
name → Rahul
age → 25
```

The value can be reused throughout the program.

---

# Variable Assignment

```python
city = "Delhi"
temperature = 35
```

Access values:

```python
print(city)
print(temperature)
```

---

# Variable Naming Rules

## Valid

```python
student_name = "John"
salary2025 = 50000
city = "Mumbai"
```

## Invalid

```python
2name = "John"
student-age = 25
class = "Python"
```

Reasons:

* Cannot start with a number
* Cannot contain hyphens
* Cannot use reserved keywords

---

# Naming Convention

Python recommends using snake_case.

Example:

```python
student_name = "Aman"
monthly_salary = 50000
```

Avoid:

```python
StudentName = "Aman"
monthlySalary = 50000
```

---

# Data Types

Python automatically determines data types.

Example:

```python
name = "Rahul"
age = 24
height = 5.8
is_student = True
```

Data Types:

| Value   | Type  |
| ------- | ----- |
| "Rahul" | str   |
| 24      | int   |
| 5.8     | float |
| True    | bool  |

---

# Checking Data Types

```python
print(type(name))
print(type(age))
print(type(height))
print(type(is_student))
```

Output:

```text
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```

---

# Multiple Variable Assignment

```python
x, y, z = 10, 20, 30
```

Print values:

```python
print(x)
print(y)
print(z)
```

---

# Variable Reassignment

Variables can change values.

```python
score = 50

score = 80
```

Final value:

```text
80
```

---

# String Formatting (f-Strings)

Recommended way:

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

# Key Functions Learned

## print()

Displays output.

```python
print("Hello")
```

## type()

Returns the data type.

```python
type(100)
```

Output:

```text
<class 'int'>
```

---

# Practice Completed

* Created variables
* Printed values
* Used f-strings
* Checked data types
* Swapped variables
* Built a student profile mini project

---

# Common Mistakes

### Forgetting Quotes Around Strings

Wrong:

```python
name = Rahul
```

Correct:

```python
name = "Rahul"
```

### Using Invalid Variable Names

Wrong:

```python
2age = 25
```

Correct:

```python
age2 = 25
```

---

# Key Takeaways

1. Python syntax is simple and beginner-friendly.
2. Variables store information.
3. Python automatically assigns data types.
4. Use meaningful variable names.
5. Follow snake_case naming convention.
6. f-strings make output cleaner and easier to read.

---

# Doubts / Questions

* What is the difference between int and float?
* How does Python store variables internally?
* Why is Python called an interpreted language?

---

# Tomorrow's Goal

Day 02:

* Data Types
* Type Conversion
* User Input
* Basic Operations

Prepare to learn how Python handles different kinds of data.
