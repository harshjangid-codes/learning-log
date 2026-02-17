# Tkinter GUI Basics in Python

## What is Tkinter?

Tkinter is Python's built-in library for creating Graphical User
Interface (GUI) applications. It allows you to create windows, buttons,
labels, text boxes, and more.

------------------------------------------------------------------------

## Creating a Window

``` python
import tkinter as tk

window = tk.Tk()
window.title("My First GUI")
window.mainloop()
```

This creates a basic application window.

------------------------------------------------------------------------

## Adding a Label

``` python
import tkinter as tk

window = tk.Tk()

label = tk.Label(window, text="Hello, Tkinter!")
label.pack()

window.mainloop()
```

Labels display text in the window.

------------------------------------------------------------------------

## Adding a Button

``` python
import tkinter as tk

def clicked():
    print("Button clicked")

window = tk.Tk()

button = tk.Button(window, text="Click Me", command=clicked)
button.pack()

window.mainloop()
```

Buttons allow user interaction.

------------------------------------------------------------------------

## Layout Management

Tkinter uses layout methods:

-   pack() → Simple automatic placement
-   grid() → Table-like placement
-   place() → Exact coordinates

Example:

``` python
label.pack()
```

------------------------------------------------------------------------

## Summary

-   Tkinter is used for GUI applications
-   Tk() creates the main window
-   Widgets include labels, buttons, text boxes
-   Layout managers organize widgets
