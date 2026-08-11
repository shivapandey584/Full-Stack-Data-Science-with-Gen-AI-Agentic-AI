# Python String Slicing

## What is String Slicing?

String slicing means **taking a part of a string**.

For example:

```python
name = "SHIVA"

print(name[0:3])
```

Output:

```text
SHI
```

We took characters from the string from index `0` to `2`.

---

## 1. String Indexing

Python starts counting characters from **0**.

Example:

```text
S  H  I  V  A
0  1  2  3  4
```

```python
name = "SHIVA"

print(name[0])
```

Output:

```text
S
```

---

## 2. Basic Slicing

The basic syntax is:

```python
string[start:end]
```

Important:

**The end index is not included.**

Example:

```python
name = "SHIVA"

print(name[0:3])
```

Output:

```text
SHI
```

Here:

* `0` → start
* `3` → stop before index 3

---

## 3. Slice From the Start

We can leave the start index empty.

```python
name = "SHIVA"

print(name[:3])
```

Output:

```text
SHI
```

This means:

**Start from the beginning and stop before index 3.**

---

## 4. Slice Until the End

We can leave the end index empty.

```python
name = "SHIVA"

print(name[2:])
```

Output:

```text
IVA
```

This means:

**Start from index 2 and go to the end.**

---

## 5. Negative Indexing

Python also allows negative indexes.

```text
S   H   I   V   A
-5 -4  -3  -2  -1
```

Example:

```python
name = "SHIVA"

print(name[-1])
```

Output:

```text
A
```

`-1` means the **last character**.

---

## 6. Negative Slicing

Example:

```python
name = "SHIVA"

print(name[-3:])
```

Output:

```text
IVA
```

This gives the **last 3 characters**.

---

## 7. Step in Slicing

We can also give a step.

Syntax:

```python
string[start:end:step]
```

Example:

```python
name = "SHIVA"

print(name[0:5:2])
```

Output:

```text
SIA
```

Here `2` means:

**Take every second character.**

---

## 8. Reverse a String

We can reverse a string using `[::-1]`.

```python
name = "SHIVA"

print(name[::-1])
```

Output:

```text
AVIHS
```

Here `-1` means move from **right to left**.

---

# More Examples

### Example 1

```python
city = "DELHI"

print(city[0:3])
```

Output:

```text
DEL
```

### Example 2

```python
city = "DELHI"

print(city[2:])
```

Output:

```text
LHI
```

### Example 3

```python
city = "DELHI"

print(city[-2:])
```

Output:

```text
HI
```

### Example 4

```python
city = "DELHI"

print(city[::-1])
```

Output:

```text
IHLED
```

---

# Important Rules

* Indexing starts from **0**.
* The end index is **not included**.
* `s[0]` → first character.
* `s[-1]` → last character.
* `s[:3]` → beginning to index 2.
* `s[2:]` → index 2 to the end.
* `s[-3:]` → last 3 characters.
* `s[::-1]` → reverse the string.

---

# String Slicing Cheat Sheet

| Code      | Meaning                      |
| --------- | ---------------------------- |
| `s[0]`    | First character              |
| `s[-1]`   | Last character               |
| `s[0:3]`  | Characters from index 0 to 2 |
| `s[:3]`   | Start to index 2             |
| `s[2:]`   | Index 2 to end               |
| `s[-3:]`  | Last 3 characters            |
| `s[::2]`  | Every second character       |
| `s[::-1]` | Reverse the string           |

---

# Practice Questions

### Question 1

```python
name = "SHIVA"
print(name[0:3])
```

What is the output?

### Question 2

```python
name = "SHIVA"
print(name[-2:])
```

What is the output?

### Question 3

```python
city = "DELHI"
print(city[::-1])
```

What is the output?

### Question 4

```python
course = "PYTHON"
print(course[0:4])
```

What is the output?

---

## Conclusion

String slicing is used to **get a part of a string**.

The main syntax is:

```python
string[start:end:step]
```

Once you understand **index, start, end, and step**, string slicing becomes very easy.

---