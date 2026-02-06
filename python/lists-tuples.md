# Lists and Tuples in Python
Lists and tuples are used to store collections of items in Python.
## Lists
A list is an ordered and mutable collection.

**Key Features**
- Ordered collection  
- Allows duplicates  
- Mutable (can change)  
- Can store different data types  

```python
fruits = ["apple", "banana", "cherry"]
print(fruits)
```
## Common List Operations
### Adding Elements
```python
fruits.append("orange")
```

### Inserting Elements
```python
fruits.insert(1, "mango")
```

### Removing Elements
```python
fruits.remove("banana")
```

### Length of List
```python
len(fruits)
```

## Tuple
A tuple is an ordered but immutable collection.

**Key Features:**
- Ordered collection  
- Immutable (cannot change)  
- Allows duplicates  
- Faster than lists

```python
coordinates = (10, 20)
print(coordinates)
```

## Single‑Element Tuple
A comma is necessary for single‑element tuples.
```python
single = (5,)
```

## Difference Between List and Tuple

| Feature        | List              | Tuple             |
|----------------|-------------------|-------------------|
| Mutability     | Mutable           | Immutable         |
| Syntax         | `[]`              | `()`              |
| Performance    | Slightly slower   | Faster            |
| Methods        | More methods      | Fewer methods     |

## When to Use What

**Use Lists When:**
- Data may change  
- Frequent insert/delete operations  

**Use Tuples When:**
- Data should not change  
- Fixed collections (coordinates, config)

## Summary
- Lists are mutable collections  
- Tuples are immutable collections  
- Both store ordered data  
- Choose based on need
