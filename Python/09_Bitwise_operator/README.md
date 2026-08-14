# Bitwise Operators in Python

Bitwise operators are used to perform operations on the **binary representation** of numbers.

Binary numbers contain only:

```text
0 and 1
```

For example:

```text
5 = 0101
3 = 0011
```

## Types of Bitwise Operators

| Operator | Name        |            |
| -------- | ----------- | ---------- |
| `&`      | Bitwise AND |            |
| `        | `           | Bitwise OR |
| `^`      | Bitwise XOR |            |
| `~`      | Bitwise NOT |            |
| `<<`     | Left Shift  |            |
| `>>`     | Right Shift |            |

---

## 1. Bitwise AND `&`

AND returns `1` only when **both bits are 1**.

### Example

```python
a = 5
b = 3

print(a & b)
```

Binary calculation:

```text
5 = 0101
3 = 0011
---------
    0001
```

Output:

```text
1
```

### Rule

```text
0 & 0 = 0
0 & 1 = 0
1 & 0 = 0
1 & 1 = 1
```

---

## 2. Bitwise OR `|`

OR returns `1` when **at least one bit is 1**.

```python
a = 5
b = 3

print(a | b)
```

Binary calculation:

```text
5 = 0101
3 = 0011
---------
    0111
```

Output:

```text
7
```

### Rule

```text
0 | 0 = 0
0 | 1 = 1
1 | 0 = 1
1 | 1 = 1
```

---

## 3. Bitwise XOR `^`

XOR returns `1` when the two bits are **different**.

```python
a = 5
b = 3

print(a ^ b)
```

Binary calculation:

```text
5 = 0101
3 = 0011
---------
    0110
```

Output:

```text
6
```

### Rule

```text
0 ^ 0 = 0
0 ^ 1 = 1
1 ^ 0 = 1
1 ^ 1 = 0
```

### Easy Trick

```text
Same      → 0
Different → 1
```

---

## 4. Bitwise NOT `~`

NOT reverses the bits.

```text
0 → 1
1 → 0
```

Example:

```python
print(~5)
```

Output:

```text
-6
```

Python follows:

```text
~n = -(n + 1)
```

Therefore:

```text
~5 = -(5 + 1)
   = -6
```

---

## 5. Left Shift `<<`

Left shift moves the bits toward the **left**.

```python
print(5 << 1)
```

Binary:

```text
5      = 0101
5 << 1 = 1010
```

`1010` = `10`

Output:

```text
10
```

### Shortcut

```text
n << 1 = n × 2
n << 2 = n × 4
n << 3 = n × 8
```

Example:

```python
print(5 << 2)
```

Output:

```text
20
```

---

## 6. Right Shift `>>`

Right shift moves the bits toward the **right**.

```python
print(10 >> 1)
```

Binary:

```text
10      = 1010
10 >> 1 = 0101
```

`0101` = `5`

Output:

```text
5
```

### Shortcut

```text
n >> 1 = n // 2
n >> 2 = n // 4
n >> 3 = n // 8
```

Example:

```python
print(20 >> 2)
```

Output:

```text
5
```

---

# Complete Example

```python
a = 5
b = 3

print("AND:", a & b)
print("OR:", a | b)
print("XOR:", a ^ b)
print("NOT:", ~a)
print("Left Shift:", a << 1)
print("Right Shift:", a >> 1)
```

Output:

```text
AND: 1
OR: 7
XOR: 6
NOT: -6
Left Shift: 10
Right Shift: 2
```

---

# Quick Revision

| Operator | Meaning     | Easy Way to Remember |               |
| -------- | ----------- | -------------------- | ------------- |
| `&`      | AND         | Both `1` → `1`       |               |
| `        | `           | OR                   | Any `1` → `1` |
| `^`      | XOR         | Different → `1`      |               |
| `~`      | NOT         | Reverse bits         |               |
| `<<`     | Left Shift  | Multiply by `2`      |               |
| `>>`     | Right Shift | Divide by `2`        |               |

---

