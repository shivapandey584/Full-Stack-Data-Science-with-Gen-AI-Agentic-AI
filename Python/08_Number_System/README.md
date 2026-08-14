# Number System

## Introduction

A **Number System** is a method of representing numbers using different digits.

In computer science and Python, we mainly use these four number systems:

1. Decimal
2. Binary
3. Octal
4. Hexadecimal

---

## 1. Decimal Number System

The Decimal number system is the number system we normally use in daily life.

* **Base:** 10
* **Digits:** 0 to 9

### Example

```python
num = 25
print(num)
```

Output:

```text
25
```

---

## 2. Binary Number System

Binary uses only **two digits: 0 and 1**.

* **Base:** 2
* **Digits:** 0 and 1

Computers use binary to represent data.

### Example

```python
num = 0b1010
print(num)
```

Output:

```text
10
```

`0b` tells Python that the number is binary.

### Decimal to Binary

```python
print(bin(10))
```

Output:

```text
0b1010
```

---

## 3. Octal Number System

Octal uses digits from **0 to 7**.

* **Base:** 8
* **Digits:** 0 to 7

### Example

```python
num = 0o12
print(num)
```

Output:

```text
10
```

`0o` tells Python that the number is octal.

### Decimal to Octal

```python
print(oct(10))
```

Output:

```text
0o12
```

---

## 4. Hexadecimal Number System

Hexadecimal uses **16 symbols**.

* **Base:** 16
* **Digits:** 0 to 9 and A to F

The values of A to F are:

```text
A = 10
B = 11
C = 12
D = 13
E = 14
F = 15
```

### Example

```python
num = 0xA
print(num)
```

Output:

```text
10
```

`0x` tells Python that the number is hexadecimal.

### Decimal to Hexadecimal

```python
print(hex(10))
```

Output:

```text
0xa
```

---

## 5. Comparison of Number Systems

| Number System | Base | Digits   | Python Prefix |
| ------------- | ---: | -------- | ------------- |
| Decimal       |   10 | 0–9      | No prefix     |
| Binary        |    2 | 0–1      | `0b`          |
| Octal         |    8 | 0–7      | `0o`          |
| Hexadecimal   |   16 | 0–9, A–F | `0x`          |

---

## 6. Python Conversion Functions

Python provides built-in functions for number conversion.

### `bin()`

Converts a number to binary.

```python
print(bin(15))
```

Output:

```text
0b1111
```

### `oct()`

Converts a number to octal.

```python
print(oct(15))
```

Output:

```text
0o17
```

### `hex()`

Converts a number to hexadecimal.

```python
print(hex(15))
```

Output:

```text
0xf
```

---

## 7. Convert Other Bases to Decimal

The `int()` function can convert a number from another base to decimal.

### Binary to Decimal

```python
print(int("1010", 2))
```

Output:

```text
10
```

### Octal to Decimal

```python
print(int("12", 8))
```

Output:

```text
10
```

### Hexadecimal to Decimal

```python
print(int("A", 16))
```

Output:

```text
10
```

---

## 8. Complete Example

```python
num = 20

print("Decimal:", num)
print("Binary:", bin(num))
print("Octal:", oct(num))
print("Hexadecimal:", hex(num))
```

Output:

```text
Decimal: 20
Binary: 0b10100
Octal: 0o24
Hexadecimal: 0x14
```

---

## 9. Quick Revision

```text
Decimal      → Base 10 → 0 to 9
Binary       → Base 2  → 0 and 1
Octal        → Base 8  → 0 to 7
Hexadecimal  → Base 16 → 0 to 9 and A to F
```

### Important Python Functions

```text
bin()  → Decimal to Binary
oct()  → Decimal to Octal
hex()  → Decimal to Hexadecimal
int()  → Convert to Decimal using a specified base
```

---

## Conclusion

Number systems are an important basic concept in **Python and Computer Science**. Understanding Decimal, Binary, Octal, and Hexadecimal will also help you learn **bitwise operators and low-level computer concepts**.
