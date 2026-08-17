# Python Math Module

## What is the Math Module?

The `math` module is a built-in Python module.

It provides many useful mathematical functions such as:

* Square root
* Power
* Factorial
* Ceiling
* Floor
* Pi
* Trigonometry

---

## 1. `import math`

This imports the complete `math` module.

### Example

```python
import math

print(math.sqrt(25))
print(math.pi)
```

Output:

```text
5.0
3.141592653589793
```

We use `math.` before the function.

---

## 2. `import math as m`

We can give a short name to the module using `as`.

### Example

```python
import math as m

print(m.sqrt(25))
print(m.pi)
```

Here:

```python
import math as m
```

means:

> Import the `math` module and give it the short name `m`.

So:

```python
math.sqrt(25)
```

becomes:

```python
m.sqrt(25)
```

---

## 3. `from math import sqrt`

We can import only the function we need.

### Example

```python
from math import sqrt

print(sqrt(25))
```

Output:

```text
5.0
```

Now we don't need to write:

```python
math.sqrt()
```

We can directly write:

```python
sqrt()
```

---

## 4. `from math import *`

The `*` means **everything**.

### Example

```python
from math import *

print(sqrt(25))
print(pi)
print(factorial(5))
```

Output:

```text
5.0
3.141592653589793
120
```

This imports all names from the `math` module.

> In normal projects, `import math` is usually easier to understand than `from math import *`.

---

# Important Math Functions

| Function           | Meaning        | Example             |
| ------------------ | -------------- | ------------------- |
| `math.sqrt()`      | Square root    | `math.sqrt(25)`     |
| `math.pow()`       | Power          | `math.pow(2, 3)`    |
| `math.factorial()` | Factorial      | `math.factorial(5)` |
| `math.ceil()`      | Round up       | `math.ceil(4.2)`    |
| `math.floor()`     | Round down     | `math.floor(4.8)`   |
| `math.fabs()`      | Absolute value | `math.fabs(-10)`    |
| `math.pi`          | Value of π     | `math.pi`           |
| `math.e`           | Euler's number | `math.e`            |

---

# Examples

## Square Root

```python
import math

print(math.sqrt(36))
```

Output:

```text
6.0
```

---

## Power

```python
import math

print(math.pow(2, 3))
```

Output:

```text
8.0
```

---

## Factorial

```python
import math

print(math.factorial(5))
```

Output:

```text
120
```

Because:

```text
5 × 4 × 3 × 2 × 1 = 120
```

---

## Ceiling

`ceil()` rounds a number **up**.

```python
import math

print(math.ceil(4.2))
```

Output:

```text
5
```

---

## Floor

`floor()` rounds a number **down**.

```python
import math

print(math.floor(4.8))
```

Output:

```text
4
```

---

# Correct Import Syntax

### 1. Import module

```python
import math
```

### 2. Import with another name

```python
import math as m
```

### 3. Import a specific function

```python
from math import sqrt
```

### 4. Import everything

```python
from math import *
```

---

# Easy Way to Remember

```text
import math
        ↓
math.sqrt()

import math as m
        ↓
m.sqrt()

from math import sqrt
        ↓
sqrt()

from math import *
        ↓
sqrt(), pi, factorial(), etc.
```

## Important

Your examples:

```python
import math
```

✅ Correct

```python
import math as m
```

✅ Correct

```python
from math import sqrt
```

✅ Correct

```python
from math import *
```

✅ Correct

---