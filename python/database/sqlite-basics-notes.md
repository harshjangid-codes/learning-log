# SQLite Database Basics in Python

## What is SQLite?

SQLite is a lightweight, file-based database. It does not require a
separate server and is built into Python.

------------------------------------------------------------------------

## Connecting to SQLite

``` python
import sqlite3

conn = sqlite3.connect("example.db")
cursor = conn.cursor()
```

This creates a database file if it does not already exist.

------------------------------------------------------------------------

## Creating a Table

``` python
cursor.execute("""
CREATE TABLE IF NOT EXISTS users (
    id INTEGER PRIMARY KEY,
    name TEXT,
    age INTEGER
)
""")
conn.commit()
```

------------------------------------------------------------------------

## Inserting Data

``` python
cursor.execute("INSERT INTO users (name, age) VALUES (?, ?)", ("Alice", 25))
conn.commit()
```

------------------------------------------------------------------------

## Reading Data

``` python
cursor.execute("SELECT * FROM users")
rows = cursor.fetchall()

for row in rows:
    print(row)
```

------------------------------------------------------------------------

## Closing the Connection

``` python
conn.close()
```

Always close the database connection after use.

------------------------------------------------------------------------

## Summary

-   SQLite is a lightweight database
-   sqlite3 module is built into Python
-   Used for small to medium applications
-   Stores data in a local file
