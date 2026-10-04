# Day 17: Inheritance and Reuse

## Goal
Learn to reuse code through inheritance.

## Learn
```python
class Animal:
    def speak(self):
        return "Some sound"

class Cat(Animal):
    def speak(self):
        return "Meow"
```

## Exercise
Create a `Vehicle` base class and subclasses for `Car` and `Bike`.

## Challenge
Add a method that returns a short description for each class.
