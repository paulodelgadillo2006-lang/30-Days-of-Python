# Day 8: Working with Files

## Goal
Learn how to read and write files in Python.

## Learn
```python
with open("data.txt", "w") as file:
    file.write("Hello from Python\n")
```

Read a file:
```python
with open("data.txt", "r") as file:
    content = file.read()
    print(content)
```

## Exercise
Create a file named `notes.txt` and write 3 lines to it.

## Challenge
Write a script that reads a file and prints the number of words in it.

## Notes
File handling is essential for automation and backend work.
