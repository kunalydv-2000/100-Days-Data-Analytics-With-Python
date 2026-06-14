# Day 02 - Data Types & Type Conversion

## 📅 Date

> Add the completion date here.

---

# 🎯 Objective

The goal of Day 02 is to understand Python data types and learn how to convert data from one type to another.

By the end of this day, I can:

* Identify Python data types
* Use the `type()` function
* Convert between data types
* Take user input
* Handle input conversion correctly
* Build simple programs using different data types

---

# 📚 Topics Covered

## 1. Python Data Types

### String (str)

```python
name = "Rahul"
```

### Integer (int)

```python
age = 25
```

### Float (float)

```python
salary = 50000.50
```

### Boolean (bool)

```python
is_student = True
```

---

## 2. Using type()

Checking the type of a variable.

```python
print(type(name))
print(type(age))
print(type(salary))
print(type(is_student))
```

---

## 3. Type Conversion

### String to Integer

```python
age = "25"
age = int(age)
```

### Integer to String

```python
score = 100
score = str(score)
```

### Integer to Float

```python
num = 10
num = float(num)
```

### Float to Integer

```python
price = 99.99
price = int(price)
```

---

## 4. User Input

Taking input from users.

```python
name = input("Enter your name: ")
```

Input values are stored as strings by default.

---

## 5. Input Conversion

```python
age = int(input("Enter your age: "))
```

```python
marks = float(input("Enter marks: "))
```

---

# 📝 Practice Exercises

### Exercise 1

Create variables and print their data types.

### Exercise 2

Convert a string into an integer.

### Exercise 3

Convert an integer into a string.

### Exercise 4

Take age as input and print age after 5 years.

### Exercise 5

Take two numbers as input and print their sum.

---

# 🚀 Mini Project

## Age Calculator

```python
name = input("Enter your name: ")
birth_year = int(input("Enter birth year: "))

current_year = 2025

age = current_year - birth_year

print(f"Hello {name}")
print(f"You are {age} years old")
```

---

# 📂 Files Created

```text
day02/
│
├── README.md
├── notes.md
├── data_types.py
├── type_conversion.py
├── user_input.py
├── age_calculator.py
└── practice.ipynb
```

---

# 💡 Key Learnings

* Every value in Python has a data type.
* User input is always stored as a string.
* Type conversion allows data transformation.
* Correct data types are important for calculations.
* Understanding data types is essential for Data Analytics.

---

# ✅ Completion Checklist

* [x] Learned String, Integer, Float, Boolean
* [x] Used type() function
* [x] Practiced type conversion
* [x] Took user input
* [x] Completed exercises
* [x] Built Age Calculator project
* [x] Pushed code to GitHub

---

# 📈 Progress

**Completed:** Day 02 / 100

### Next Day

➡️ Day 03 – Strings and String Operations
