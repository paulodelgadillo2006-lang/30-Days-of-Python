# Day 10: Modules and Imports

## Goal
Learn how to organize code into reusable files.

## Learn
A module is a Python file.

Create `greetings.py`:
```python
def hello(name):
    return "Hello, " + name
```

Then import it:
```python
import greetings

print(greetings.hello("Nina"))
```

## Exercise
Create two files:
- `math_tools.py`
- `main.py`

Then import and use a function from the first file.

## Challenge
Build a simple app with a `calculator.py` and a `main.py` file.
