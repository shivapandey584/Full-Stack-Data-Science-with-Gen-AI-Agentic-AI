# Python Data Type Casting

## What is Type Casting?

**Type Casting** means changing one data type into another data type.

For example:

* Integer → String
* String → Integer
* Float → Integer
* Integer → Float

Python provides some built-in functions for type casting.

---

## Common Type Casting Functions

| Function  | Used For           |
| --------- | ------------------ |
| `int()`   | Convert to Integer |
| `float()` | Convert to Float   |
| `str()`   | Convert to String  |
| `bool()`  | Convert to Boolean |

---

## 1. Convert String to Integer

We can use `int()` to convert a string into an integer.

```python
age = "25"

age = int(age)

print(age)
print(type(age))
```

### Output

```text
25
<class 'int'>
```

---

## 2. Convert Integer to Float

We can use `float()` to convert an integer into a float.

```python
num = 10

num = float(num)

print(num)
print(type(num))
```

### Output

```text
10.0
<class 'float'>
```

---

## 3. Convert Integer to String

We can use `str()` to convert an integer into a string.

```python
age = 25

age = str(age)

print(age)
print(type(age))
```

### Output

```text
25
<class 'str'>
```

---

## 4. Convert Float to Integer

We can use `int()` to convert a float into an integer.

```python
price = 25.8

price = int(price)

print(price)
```

### Output

```text
25
```

**Note:** The decimal part is removed. It does not round the number.

---

## 5. Convert String to Float

We can use `float()` to convert a string into a float.

```python
price = "99.50"

price = float(price)

print(price)
print(type(price))
```

### Output

```text
99.5
<class 'float'>
```

---

## 6. Convert Value to Boolean

We can use `bool()` to convert a value into `True` or `False`.

```python
x = 10

print(bool(x))
```

### Output

```text
True
```

Another example:

```python
x = 0

print(bool(x))
```

### Output

```text
False
```

---

## Type Casting Example

```python
age = "25"
salary = "50000.50"

age = int(age)
salary = float(salary)

print(age)
print(salary)
```

### Output

```text
25
50000.5
```

---

## Important Point

Not every value can be converted into every data type.

For example:

```python
name = "Shiva"

age = int(name)
```

This will give an **error** because `"Shiva"` cannot be converted into an integer.

---

## User Input and Type Casting

The `input()` function always takes input as a **string**.

Example:

```python
age = input("Enter your age: ")

print(type(age))
```

If you enter `25`, the type will still be:

```text
<class 'str'>
```

To convert it into an integer:

```python
age = int(input("Enter your age: "))

print(type(age))
```

Now the type will be:

```text
<class 'int'>
```

---

## Quick Summary

```text
int()    → Integer
float()  → Float
str()    → String
bool()   → Boolean
```

### Example

```python
x = "100"

x = int(x)

print(x)
print(type(x))
```

**Type Casting = Changing one data type into another data type.**

