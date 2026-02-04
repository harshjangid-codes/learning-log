# Python Operators

Operators are symbols used to perform operations on variables and values.

## Arithmetic Operators
Used for mathematical operations.

| Operator | Meaning         | Example |
|----------|-----------------|---------|
| `+`      | Addition        | `a + b` |
| `-`      | Subtraction     | `a - b` |
| `*`      | Multiplication  | `a * b` |
| `/`      | Division        | `a / b` |
| `//`     | Floor Division  | `a // b`|
| `%`      | Modulus         | `a % b` |
| `**`     | Exponentiation  | `a ** b`|


**Example:**
```python
a = 10
b = 3

print(a + b)   # 13
print(a - b)   # 7
print(a * b)   # 30
print(a / b)   # 3.333...
print(a // b)  # 3
print(a % b)   # 1
print(a ** b)  # 1000
```
## Relational Operators
Used to compare two values.

| Operator | Meaning                  |
|----------|--------------------------|
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

**Example:**
```python
a = 10
b = 5

print(a == b)  # False
print(a != b)  # True
print(a > b)   # True
print(a < b)   # False
print(a >= b)  # True
print(a <= b)  # False
```
## Logical Operators
Used to combine conditional statements.

| Operator | Meaning                          |
|----------|----------------------------------|
| `and`    | True if both conditions are true |
| `or`     | True if at least one is true     |
| `not`    | Reverses the condition           |

**Example:**
```python
a = True
b = False

print(a and b)  # False
print(a or b)   # True
print(not a)    # False
```
## Assignment Operators
Used to assign values to variables.

| Operator | Example  |
|----------|----------|
| `=`      | `a = 5`  |
| `+=`     | `a += 2` |
| `-=`     | `a -= 2` |
| `*=`     | `a *= 2` |
| `/=`     | `a /= 2` |
| `%=`     | `a %= 2` |
| `**=`    | `a **= 2`|
| `//=`    | `a //= 2`|

**Example:**
```python
a = 10
a += 5   # a = 15
a *= 2   # a = 30
print(a)  # 30
```
## Conditional (Ternary) Operator
Python supports a one-line conditional expression.

**Example:**
```python
age = 18
result = "Eligible" if age >= 18 else "Not eligible"
print(result)  # Eligible
```
## Bitwise Operators
Used to perform operations at the bit level.

| Operator | Meaning    |
|----------|------------|
| `&`      | AND        |
| `|`      | OR         |
| `^`      | XOR        |
| `~`      | NOT        |
| `<<`     | Left Shift |
| `>>`     | Right Shift|

**Example:**
```python
a = 6   # 110 in binary
b = 3   # 011 in binary

print(a & b)   # 2 (010)
print(a | b)   # 7 (111)
print(a ^ b)   # 5 (101)
print(~a)      # -(a + 1) → -7
print(a << 1)  # 12 (1100)
print(a >> 1)  # 3 (011)
```
## Summary
- Operators perform actions on values
- Python supports arithmetic, logical, relational, and bitwise operators
- Assignment operators simplify variable updates
