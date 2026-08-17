# Python `input()` Function

## 📌 What is `input()`?

The `input()` function is used to **take information from the user**.

For example, if we want the user to enter their name, we can use `input()`.

## Syntax

```python
input("Message")
```

## Example

```python
name = input("Enter your name: ")

print(name)
```

If the user enters:

```text
Shiva
```

Output:

```text
Shiva
```

---

## 🔹 Important Point

`input()` always takes the user's input as a **string**.

Example:

```python
age = input("Enter your age: ")

print(type(age))
```

If the user enters `21`, the output will be:

```text
<class 'str'>
```

---

## 🔹 Taking Integer Input

If you want to take an integer, use `int()`.

```python
age = int(input("Enter your age: "))

print(age)
```

Now if the user enters `21`, Python stores it as an integer.

```python
print(type(age))
```

Output:

```text
<class 'int'>
```

---

## 🔹 Taking Float Input

For decimal numbers, use `float()`.

```python
price = float(input("Enter the price: "))

print(price)
```

If the user enters `99.50`:

```text
99.5
```

---

## 🔹 Input with Calculation

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print(a + b)
```

If the user enters:

```text
10
20
```

Output:

```text
30
```

---

## 🔹 Taking Multiple Inputs

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))

print(name)
print(age)
```

---

## 🔹 Input with F-String

We can use input values with an f-string.

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))

print(f"My name is {name} and I am {age} years old.")
```

Output:

```text
My name is Shiva and I am 21 years old.
```

---

## ❌ Common Mistake

This will give an error:

```python
age = input("Enter your age: ")

print(age + 5)
```

Why?

Because `input()` gives a **string**.

## ✅ Correct Way

```python
age = int(input("Enter your age: "))

print(age + 5)
```

If the user enters `21`:

```text
26
```

---

## 📊 Quick Summary

| Code             | Meaning              |
| ---------------- | -------------------- |
| `input()`        | Takes user input     |
| `int(input())`   | Takes integer input  |
| `float(input())` | Takes decimal input  |
| `type(input())`  | Shows the input type |

## ⭐ Remember

```python
name = input("Enter your name: ")
```

➡️ `input()` is used to **take data from the user**.

```python
age = int(input("Enter your age: "))
```

➡️ `int()` converts the input into an **integer**.

```python
salary = float(input("Enter your salary: "))
```

➡️ `float()` converts the input into a **decimal number**.

---