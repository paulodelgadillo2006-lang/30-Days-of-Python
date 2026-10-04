# Day 15: Classes and Objects

## Goal
Practice class creation and attribute handling.

## Exercise
```python
class Book:
    def __init__(self, title, author):
        self.title = title
        self.author = author

    def info(self):
        return self.title + " by " + self.author

book = Book("Clean Code", "Robert C. Martin")
print(book.info())
```

## Challenge
Create a `Laptop` class with model, ram, and a `details()` method.
