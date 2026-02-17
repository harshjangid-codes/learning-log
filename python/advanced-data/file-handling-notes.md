# File Handling, CSV, and Exception Handling in Python

## File Handling

File handling allows reading from and writing to files.

### Reading a File

``` python
with open("file.txt", "r") as f:
    content = f.read()
    print(content)
```

### Writing to a File

``` python
with open("file.txt", "w") as f:
    f.write("Hello World")
```

### Appending to a File

``` python
with open("file.txt", "a") as f:
    f.write("\nNew Line")
```

------------------------------------------------------------------------

## Exception Handling

Exceptions help handle runtime errors gracefully.

### Basic Example

``` python
try:
    num = int(input("Enter number: "))
except ValueError:
    print("Invalid number")
```

### File Example

``` python
try:
    with open("missing.txt") as f:
        print(f.read())
except FileNotFoundError:
    print("File not found")
```

------------------------------------------------------------------------

## CSV Handling

CSV (Comma-Separated Values) files store tabular data.

### Reading CSV

``` python
import csv

with open("data.csv") as f:
    reader = csv.reader(f)
    for row in reader:
        print(row)
```

### Writing CSV

``` python
import csv

with open("data.csv", "w", newline="") as f:
    writer = csv.writer(f)
    writer.writerow(["Name", "Age"])
    writer.writerow(["Alice", 25])
```

------------------------------------------------------------------------

## Summary

-   File handling enables reading and writing files
-   Exception handling prevents program crashes
-   CSV module helps work with tabular data
