# Day 9: Error Handling

## Goal
Handle problems without crashing the program.

## Learn
```python
try:
    number = int("abc")
except ValueError:
    print("That is not a valid integer.")
```

## Exercise
Write a script that asks for a number and catches invalid input.

## Challenge
Build a little calculator that handles division by zero safely.

## Notes
Real apps fail sometimes. Good developers handle problems gracefully.
