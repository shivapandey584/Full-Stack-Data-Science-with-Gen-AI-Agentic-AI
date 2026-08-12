# Python `print()` Function

## Introduction

The `print()` function is used to **display output on the screen**.

It is one of the most commonly used functions in Python.

### Basic Syntax

```python
print("Hello World")
```

**Output:**

```text
Hello World
```

---

## 1. Print Result with String

We can print text and variables together using the `print()` function.

```python
name = "Shiva"
age = 21

print("My name is", name)
print("My age is", age)
```

**Output:**

```text
My name is Shiva
My age is 21
```

---

## 2. Code Optimization

Code optimization means writing code in a **simple, clean, and efficient way**.

### Without Optimization

```python
name = "Shiva"
print("My name is")
print(name)
```

### Optimized Code

```python
name = "Shiva"
print("My name is", name)
```

The optimized code is shorter and easier to understand.

---

## 3. `format()` Method

The `format()` method is used to insert variables into a string.

### Example

```python
name = "Shiva"
age = 21

print("My name is {} and my age is {}".format(name, age))
```

**Output:**

```text
My name is Shiva and my age is 21
```

### Another Example

```python
name = "Rahul"
salary = 30000

print("My name is {} and my salary is {}".format(name, salary))
```

**Output:**

```text
My name is Rahul and my salary is 30000
```

---

## 4. F-String Method

F-string is a modern and easy way to insert variables into strings.

We use `f` before the string.

### Example

```python
name = "Shiva"
age = 21

print(f"My name is {name} and my age is {age}")
```

**Output:**

```text
My name is Shiva and my age is 21
```

### Why Use F-String?

F-strings are:

* Easy to write
* Easy to read
* Short
* Commonly used in modern Python

### Example

```python
product = "Laptop"
price = 50000

print(f"The price of {product} is {price}")
```

**Output:**

```text
The price of Laptop is 50000
```

---

## 5. `end` Statement

By default, `print()` moves the cursor to a **new line** after printing.

We can change this behavior using the `end` parameter.

### Default Behavior

```python
print("Hello")
print("World")
```

**Output:**

```text
Hello
World
```

### Using `end`

```python
print("Hello", end=" ")
print("World")
```

**Output:**

```text
Hello World
```

### Another Example

```python
print("Python", end="-")
print("Programming")
```

**Output:**

```text
Python-Programming
```

---

## 6. `sep` (Separator)

The `sep` parameter is used to define the separator between multiple values.

### Default Separator

The default separator is a space.

```python
print("Python", "Java", "SQL")
```

**Output:**

```text
Python Java SQL
```

### Using `sep`

```python
print("Python", "Java", "SQL", sep=", ")
```

**Output:**

```text
Python, Java, SQL
```

### Another Example

```python
print(10, 20, 30, sep="-")
```

**Output:**

```text
10-20-30
```

---

## 7. `end` and `sep` Together

We can use both `sep` and `end` in the same `print()` statement.

```python
print("Python", "SQL", "Power BI", sep=" | ", end=" --> ")
print("Data Analyst")
```

**Output:**

```text
Python | SQL | Power BI --> Data Analyst
```

---

## Quick Revision

| Topic             | Purpose                              |
| ----------------- | ------------------------------------ |
| `print()`         | Display output                       |
| String + variable | Print text with values               |
| `format()`        | Insert values into a string          |
| F-string          | Easy and modern string formatting    |
| `end`             | Control what comes after printing    |
| `sep`             | Control the separator between values |
| Code optimization | Write clean and simple code          |

---

## Practice Examples

### Example 1

```python
name = "Shiva"
print("Hello", name)
```

### Example 2

```python
name = "Shiva"
age = 21

print("My name is {} and I am {} years old".format(name, age))
```

### Example 3

```python
name = "Shiva"
age = 21

print(f"My name is {name} and I am {age} years old")
```

### Example 4

```python
print("A", "B", "C", sep="-")
```

### Example 5

```python
print("Hello", end=" ")
print("Python")
```

## Conclusion

The Python `print()` function is used to display output.

Important concepts to remember:

1. `print()`
2. Printing strings and variables
3. Code optimization
4. `format()` method
5. F-string method
6. `end` parameter
7. `sep` parameter

---