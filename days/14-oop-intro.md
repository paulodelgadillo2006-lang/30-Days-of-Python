# Day 14: Introduction to Object-Oriented Programming

## Goal
Understand the idea of classes and objects.

## Learn
```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        return self.name + " says woof!"

my_dog = Dog("Luna")
print(my_dog.bark())
```

## Exercise
Create a `Car` class with a `brand` and `drive()` method.

## Challenge
Create a `Student` class with `name`, `age`, and `info()`.

## Notes
OOP helps organize bigger codebases and is used widely in real projects.
