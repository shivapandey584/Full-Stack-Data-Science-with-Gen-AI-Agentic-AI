# Swapping Variables in Python

## What is Swapping?

**Swapping** means exchanging the values of two variables.

For example:

```text
Before swapping:
a = 10
b = 20

After swapping:
a = 20
b = 10
```

---

## 1. Swapping Using a Third Variable

This is the traditional method.

```python
a = 10
b = 20

temp = a
a = b
b = temp

print(a)
print(b)
```

Output:

```text
20
10
```

### How it works

```text
temp = a   → temp = 10
a = b      → a = 20
b = temp   → b = 10
```

Here, `temp` temporarily stores the value of `a`.

---

## 2. Swapping Without a Third Variable

Python provides an easy way to swap variables.

```python
a = 10
b = 20

a, b = b, a

print(a)
print(b)
```

Output:

```text
20
10
```

This is the **recommended Python method**.

---

## 3. Swapping Using Arithmetic Operators

We can also swap numbers using `+` and `-`.

```python
a = 10
b = 20

a = a + b
b = a - b
a = a - b

print(a)
print(b)
```

Output:

```text
20
10
```

### Important

This method works with numbers, but Python's:

```python
a, b = b, a
```

is simpler and safer.

---

## 4. Swapping Using XOR

For integer values, swapping can also be done using XOR.

```python
a = 10
b = 20

a = a ^ b
b = a ^ b
a = a ^ b

print(a)
print(b)
```

Output:

```text
20
10
```

This is related to the **bitwise XOR (`^`) operator**.

---

# Best Method in Python

The easiest and most readable method is:

```python
a = 10
b = 20

a, b = b, a
```

Python automatically exchanges the values.

---

# Real-Life Example

Suppose:

```python
name1 = "Shiva"
name2 = "Rahul"
```

Swap them:

```python
name1, name2 = name2, name1

print(name1)
print(name2)
```

Output:

```text
Rahul
Shiva
```

---

# Quick Revision

| Method          | Example       | Recommended         |
| --------------- | ------------- | ------------------- |
| Third variable  | `temp = a`    | Yes                 |
| Python swapping | `a, b = b, a` | ⭐ Best              |
| Arithmetic      | `a = a + b`   | Sometimes           |
| XOR             | `a = a ^ b`   | Mainly for learning |

---

# Practice Questions

### Question 1

Swap two numbers:

```python
a = 50
b = 100
```

Expected output:

```text
a = 100
b = 50
```

### Question 2

Swap these variables:

```python
x = 25
y = 75
```

### Question 3

Swap two strings:

```python
first_name = "Shiva"
last_name = "Pandey"
```

### Question 4

Swap three variables:

```python
a = 10
b = 20
c = 30
```

After swapping:

```text
a = 30
b = 10
c = 20
```

## Key Point

In Python, remember:

```python
a, b = b, a
```

**It swaps the values of `a` and `b` without using a third variable.**

----