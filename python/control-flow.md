# Control Flow in Python

Control flow determines the order in which statements are executed in a program.

## Conditional Statements

### if Statement
Executes a block of code if the condition is `True`.

```python
a = 10
b = 5

if a > b:
    print("a is greater than b")
```

### if–else Statement
Executes one block if the condition is true, otherwise executes another block.

```python
a = 5
b = 10

if a > b:
    print("a is greater than b")
else:
    print("b is greater than a")
```

### if–elif–else Statement
Used to check multiple conditions.

```python
marks = 85

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
else:
    print("Grade C")
```

## Loops
Loops are used to repeat a block of code.

### for Loop
Iterates over a sequence.

```python
for i in range(5):
    print(i)
```

### while Loop
Repeats as long as a condition remains true.

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

## Loop Control Statements

### break
Stops the loop immediately.

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

### continue
Skips the current iteration and continues with the next one.

```python
for i in range(5):
    if i == 3:
        continue
    print(i)
```

### pass
Acts as a placeholder when a statement is required syntactically.

```python
if True:
    pass
```

## Summary
- Control flow directs program execution  
- Conditional statements make decisions  
- Loops repeat tasks efficiently  
- `break`, `continue`, and `pass` control loop behavior
