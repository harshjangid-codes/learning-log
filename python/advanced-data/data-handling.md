# Python Data Handling (Dictionaries, Sets, JSON)

## Dictionaries

A dictionary stores data as key-value pairs. It is mutable and allows
fast lookup using keys.

### Example

``` python
my_dict = {
    "name": "John",
    "age": 30,
    "city": "New York"
}

print(my_dict["name"])
```

### Key Points

-   Keys must be unique
-   Mutable (can add, update, delete items)
-   Unordered collection
-   Efficient for data retrieval

------------------------------------------------------------------------

## Sets

A set stores unique elements and automatically removes duplicates.

### Example

``` python
my_set = {1, 2, 3}
my_set.add(4)
print(my_set)
```

### Common Operations

``` python
A = {1, 2, 3}
B = {3, 4, 5}

print(A | B)  # Union
print(A & B)  # Intersection
print(A - B)  # Difference
```

### Key Points

-   No duplicate values
-   Mutable collection
-   Unordered
-   Useful for mathematical operations

------------------------------------------------------------------------

## JSON Handling

JSON (JavaScript Object Notation) is used for storing and exchanging
data.

Python provides the `json` module to work with JSON data.

### Convert Python → JSON

``` python
import json

data = {"name": "Alice", "age": 25}
json_string = json.dumps(data)
print(json_string)
```

### Convert JSON → Python

``` python
python_data = json.loads(json_string)
print(python_data["name"])
```

### Uses of JSON

-   Web APIs
-   Configuration files
-   Data storage
-   Communication between systems

------------------------------------------------------------------------

## Summary

-   Dictionaries store key-value data
-   Sets store unique elements
-   JSON is widely used for data exchange
-   Python's `json` module simplifies JSON handling
