# Day 03 - Strings & String Operations

## 📅 Date

> Add the completion date here.

---

# 🎯 Objective

The goal of Day 03 is to understand Python Strings and learn how to manipulate text efficiently.

Strings are one of the most important data types in Data Analytics because real-world datasets often contain:

* Customer Names
* Product Names
* Cities
* Email Addresses
* Reviews
* Categories

By the end of this day, I can:

* Create strings
* Access characters using indexing
* Extract text using slicing
* Use common string methods
* Format strings using f-strings
* Build simple text-processing programs

---

# 📚 Topics Covered

## 1. What is a String?

A string is a sequence of characters enclosed in quotes.

Example:

```python
name = "Rahul"
city = "Delhi"
course = "Data Analytics"
```

---

## 2. String Indexing

Accessing individual characters using their position.

Example:

```python
name = "Python"

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

## 3. Negative Indexing

Accessing characters from the end of a string.

Example:

```python
name = "Python"

print(name[-1])
```

Output:

```text
n
```

---

## 4. String Slicing

Extracting a portion of a string.

Example:

```python
name = "DataAnalytics"

print(name[0:4])
print(name[4:])
```

Output:

```text
Data
Analytics
```

---

## 5. String Length

Using the `len()` function.

```python
name = "Python"

print(len(name))
```

Output:

```text
6
```

---

## 6. String Methods

### upper()

```python
name = "python"

print(name.upper())
```

### lower()

```python
name = "PYTHON"

print(name.lower())
```

### title()

```python
course = "data analytics"

print(course.title())
```

### capitalize()

```python
city = "delhi"

print(city.capitalize())
```

### replace()

```python
sentence = "I like Java"

print(sentence.replace("Java", "Python"))
```

### strip()

```python
name = "   Rahul   "

print(name.strip())
```

---

## 7. String Concatenation

Combining strings together.

```python
first_name = "Rahul"
last_name = "Sharma"

full_name = first_name + " " + last_name

print(full_name)
```

---

## 8. Membership Operators

Checking if text exists inside a string.

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

## 9. String Formatting

Using f-strings.

```python
name = "Rahul"
age = 25

print(f"My name is {name}")
print(f"I am {age} years old")
```

---

## 10. Escape Characters

### New Line

```python
print("Python\nData Analytics")
```

### Tab

```python
print("Name\tAge")
```

---

## 11. Useful String Functions

### count()

```python
word = "banana"

print(word.count("a"))
```

### find()

```python
word = "Analytics"

print(word.find("t"))
```

### startswith()

```python
email = "user@gmail.com"

print(email.startswith("user"))
```

### endswith()

```python
email = "user@gmail.com"

print(email.endswith(".com"))
```

---

# 📝 Practice Exercises

### Exercise 1

Create a string and print:

* First character
* Last character

### Exercise 2

Print:

* Length
* Uppercase version
* Lowercase version

### Exercise 3

Replace a word in a sentence.

### Exercise 4

Take user input and display a welcome message using f-strings.

### Exercise 5

Check if a word exists inside a string.

---

# 🚀 Mini Project

## User Profile Formatter

```python
name = input("Enter your name: ")
city = input("Enter your city: ")
course = input("Enter your course: ")

print("\n----- PROFILE -----")
print(f"Name   : {name.title()}")
print(f"City   : {city.title()}")
print(f"Course : {course.title()}")
```

---

# 📂 Files Created

```text
day03/
│
├── README.md
├── notes.md
├── strings.py
├── string_methods.py
├── string_slicing.py
├── profile_formatter.py
└── practice.ipynb
```

---

# 💡 Key Learnings

* Strings store textual data.
* Indexing allows access to individual characters.
* Slicing extracts portions of text.
* String methods simplify text manipulation.
* f-strings provide clean formatting.
* Text processing is a fundamental skill in Data Analytics.

---

# ✅ Completion Checklist

* [ ] Learned string fundamentals
* [ ] Practiced indexing
* [ ] Practiced slicing
* [ ] Used common string methods
* [ ] Applied string formatting
* [ ] Completed exercises
* [ ] Built User Profile Formatter
* [ ] Pushed code to GitHub

---

# 📈 Progress

**Completed:** Day 03 / 100

### Next Day

➡️ Day 04 – Lists & List Operations
