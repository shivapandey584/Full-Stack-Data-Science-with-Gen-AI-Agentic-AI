# Python Operators

## What are Operators?

Operators are special symbols used to perform operations on values and variables.

Example:

```python
a = 10
b = 5

print(a + b)
```

Output:

```text
15
```

---

## Types of Operators in Python

Python has several types of operators:

1. Arithmetic Operators
2. Assignment Operators
3. Comparison Operators
4. Logical Operators
5. Identity Operators
6. Membership Operators
7. Bitwise Operators

---

# 1. Arithmetic Operators

Arithmetic operators are used for mathematical calculations.

| Operator | Name           | Example   | Result |
| -------- | -------------- | --------- | ------ |
| `+`      | Addition       | `10 + 5`  | `15`   |
| `-`      | Subtraction    | `10 - 5`  | `5`    |
| `*`      | Multiplication | `10 * 5`  | `50`   |
| `/`      | Division       | `10 / 5`  | `2.0`  |
| `%`      | Modulus        | `10 % 3`  | `1`    |
| `//`     | Floor Division | `10 // 3` | `3`    |
| `**`     | Exponent       | `2 ** 3`  | `8`    |

### Example

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a // b)
print(a ** b)
```

---

# 2. Assignment Operators

Assignment operators are used to assign values to variables.

| Operator | Example  | Meaning     |
| -------- | -------- | ----------- |
| `=`      | `x = 10` | Assign      |
| `+=`     | `x += 5` | `x = x + 5` |
| `-=`     | `x -= 5` | `x = x - 5` |
| `*=`     | `x *= 5` | `x = x * 5` |
| `/=`     | `x /= 5` | `x = x / 5` |

### Example

```python
x = 10

x += 5
print(x)
```

Output:

```text
15
```

---

# 3. Comparison Operators

Comparison operators compare two values.

The result is always **True** or **False**.

| Operator | Meaning                  |
| -------- | ------------------------ |
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

### Example

```python
a = 10
b = 5

print(a > b)
print(a < b)
print(a == b)
print(a != b)
```

Output:

```text
True
False
False
True
```

---
Logical operators are used to combine conditions.

| Operator | Meaning                             |
| -------- | ----------------------------------- |
| `and`    | Both conditions must be True        |
| `or`     | At least one condition must be True |
| `not`    | Reverses the result                 |

### Example

```python
age = 21

print(age >= 18 and age <= 60)
```

Output:

```text
True
```

### `or` Example

```python
age = 15

print(age < 18 or age > 60)
```

Output:

```text
True
```

### `not` Example

```python
x = True

print(not x)
```

Output:

```text
False
```

---

# 5. Identity Operators

Identity operators check whether two variables refer to the same object.

| Operator | Meaning           |
| -------- | ----------------- |
| `is`     | Same object       |
| `is not` | Different objects |

Example:

```python
a = [1, 2, 3]
b = a

print(a is b)
```

Output:

```text
True
```

---

# 6. Membership Operators

Membership operators check whether a value exists inside a sequence such as a string, list, or tuple.

| Operator | Meaning              |
| -------- | -------------------- |
| `in`     | Value exists         |
| `not in` | Value does not exist |

### Example

```python
name = "Shiva"

print("S" in name)
print("x" not in name)
```

Output:

```text
True
True
```

---

# 7. Bitwise Operators

Bitwise operators work with binary numbers.

| Operator | Name        |    |
| -------- | ----------- | -- |
| `&`      | AND         |    |
| `        | `           | OR |
| `^`      | XOR         |    |
| `~`      | NOT         |    |
| `<<`     | Left Shift  |    |
| `>>`     | Right Shift |    |

Example:

```python
a = 5
b = 3

print(a & b)
print(a | b)
```

---

# Important Difference

### `=` vs `==`

`=` is used for **assignment**.

```python
x = 10
```

`==` is used for **comparison**.

```python
print(x == 10)
```

Output:

```text
True
```

---

# Real-Life Example

```python
age = 21
salary = 30000

print(age >= 18)
print(salary > 25000)
```

Output:

```text
True
True
```

---

# Summary

| Operator Type | Main Use                     |
| ------------- | ---------------------------- |
| Arithmetic    | Mathematical calculations    |
| Assignment    | Assign/update values         |
| Comparison    | Compare values               |
| Logical       | Combine conditions           |
| Identity      | Check object identity        |
| Membership    | Check whether a value exists |
| Bitwise       | Work with binary values      |

## Practice

Try to solve these:

```python
a = 20
b = 6

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a // b)
```

### Questions

1. What is the difference between `=` and `==`?
2. What is the output of `15 % 4`?
3. What is the output of `15 // 4`?
4. Which operator is used for "not equal"?
5. Which operator checks membership?
6. What is the difference between `and` and `or`?

-----