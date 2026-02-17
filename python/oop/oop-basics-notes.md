# Object-Oriented Programming (OOP) Basics in Python

## What is OOP?

Object-Oriented Programming is a programming paradigm based on objects
and classes. It helps organize code into reusable and structured
components.

------------------------------------------------------------------------

## Classes and Objects

A class is a blueprint for creating objects. An object is an instance of
a class.

### Example

``` python
class Person:
    def __init__(self, name):
        self.name = name

p = Person("Harsh")
print(p.name)
```

------------------------------------------------------------------------

## Constructor (**init**)

The constructor initializes object attributes when an object is created.

``` python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

s = Student("Alice", 20)
print(s.name, s.age)
```

------------------------------------------------------------------------

## Methods

Methods are functions defined inside a class.

``` python
class Dog:
    def speak(self):
        print("Bark")

d = Dog()
d.speak()
```

------------------------------------------------------------------------

## Encapsulation

Encapsulation means restricting direct access to variables.

``` python
class Bank:
    def __init__(self):
        self.__balance = 1000
```

Double underscore makes variables private.

------------------------------------------------------------------------

## Inheritance

Inheritance allows one class to use properties of another class.

``` python
class Animal:
    def speak(self):
        print("Animal sound")

class Dog(Animal):
    pass

d = Dog()
d.speak()
```

------------------------------------------------------------------------

## Summary

-   Classes are blueprints for objects
-   Objects are instances of classes
-   **init** initializes object data
-   Methods define behavior
-   Encapsulation protects data
-   Inheritance promotes code reuse
