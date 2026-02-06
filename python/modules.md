# Python Modules
A module in Python is a file containing Python code such as functions, variables, or classes.  
Modules help organize code and promote reuse.

## Importing Modules
Modules are imported using the `import` keyword.
```python
import math
print(math.sqrt(16))  # 4.0
```

## Import Specific Items
You can import specific functions or variables from a module.
```python
from math import sqrt
print(sqrt(25))  # 5.0
```

## Using Aliases
Modules can be imported with shorter names using `as`.
```python
import math as m
print(m.pi)  # 3.141592653589793
```

## Built‑in Modules Example
Python provides many built‑in modules.
```python
import datetime
print(datetime.date.today())  # e.g., 2026-02-06
```

## Creating Your Own Module
Create a file named `mymodule.py`, write functions or variables inside it, then import it in another Python file.

**mymodule.py**
```python
def greet():
    print("Hello from module")
```

**main.py**
```python
import mymodule
mymodule.greet()  # Hello from module
```

## Why Modules Are Useful
- Code organization  
- Reusability  
- Easier maintenance  
- Cleaner projects

## Summary
- Modules are reusable Python files  
- Imported using `import`  
- Can contain functions, classes, and variables  
- Help structure larger programs
