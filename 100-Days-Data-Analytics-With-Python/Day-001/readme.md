# Day 01 - Python Setup & Variables

## 📅 Date

> Add the date when you complete this day.

---

# 🎯 Objective

The goal of Day 01 is to set up the Python development environment and understand the concept of variables.

By the end of this lesson, I will be able to:

* Install Python
* Configure VS Code for Python development
* Use Jupyter Notebook
* Create and run Python scripts
* Understand variables and data storage
* Follow Python naming conventions
* Print output using Python

---

# 📚 Topics Covered

## 1. Python Installation

Installed Python and verified installation using:

```bash
python --version
```

or

```bash
python3 --version
```

---

## 2. Development Environment Setup

### Tools Installed

* Python
* VS Code
* Python Extension
* Jupyter Extension
* Pylance Extension

---

## 3. First Python Program

Created and executed the first Python script.

```python
print("Hello Data Analytics!")
print("Welcome to Day 1")
```

### Output

```text
Hello Data Analytics!
Welcome to Day 1
```

---

## 4. Variables

Variables are containers used to store data.

Example:

```python
name = "Rahul"
age = 25
salary = 50000
```

---

## 5. Variable Naming Rules

### Valid Variable Names

```python
student_name = "John"
salary2025 = 50000
city = "Delhi"
```

### Invalid Variable Names

```python
2name = "John"
student-age = 20
class = "Python"
```

---

## 6. Data Types Introduced

| Data Type | Example    |
| --------- | ---------- |
| String    | `"Python"` |
| Integer   | `25`       |
| Float     | `5.8`      |
| Boolean   | `True`     |

Example:

```python
name = "Rahul"
age = 25
height = 5.8
is_student = True
```

Checking data types:

```python
print(type(name))
print(type(age))
print(type(height))
print(type(is_student))
```

---

## 7. String Formatting

Used f-strings for readable output.

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

# 📝 Practice Exercises

### Exercise 1

Create variables:

```python
name
age
city
```

Print all values.

---

### Exercise 2

Create product information variables.

```python
product_name
price
quantity
```

Display formatted output.

---

### Exercise 3

Store your personal details and print them using f-strings.

---

### Exercise 4

Swap two variables.

```python
a = 10
b = 20

a, b = b, a
```

---

# 🚀 Mini Project

## Student Profile Generator

Created a simple profile card using variables.

```python
name = "Rahul"
age = 22
course = "Data Analytics"
city = "Delhi"

print("----- Student Profile -----")
print(f"Name : {name}")
print(f"Age : {age}")
print(f"Course : {course}")
print(f"City : {city}")
```

---

# 📂 Files Created

```text
day01/
│
├── README.md
├── hello_python.py
├── variables.py
├── student_profile.py
├── practice.ipynb
└── notes.md
```

---

# 💡 Key Learnings

* Python is easy to read and write.
* Variables store information for later use.
* Python automatically identifies data types.
* f-strings provide clean and professional output formatting.
* Following naming conventions improves code readability.

---

# 📌 Challenges Faced

> Add any issues faced during setup or coding.

Example:

* Python PATH issue
* VS Code interpreter selection
* Jupyter installation problems

---

# 🔍 Resources Used

* Python Documentation
* VS Code Documentation
* Class Notes
* Practice Exercises

---

# ✅ Completion Checklist

* [x] Python installed
* [x] VS Code configured
* [x] Jupyter Notebook working
* [x] First Python program executed
* [x] Variables understood
* [x] Practice exercises completed
* [x] Mini project completed
* [x] Code pushed to GitHub

---

# 📈 Progress

**Day Completed:** 1 / 100

Current Phase:

✅ Python Fundamentals (Day 1–20)

---

## Next Day

➡️ Day 02 – Data Types and Type Conversion
