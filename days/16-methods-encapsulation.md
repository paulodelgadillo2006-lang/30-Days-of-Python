# Day 16: Methods and Encapsulation

## Goal
Learn how methods work and why encapsulation matters.

## Learn
```python
class Account:
    def __init__(self, balance):
        self.__balance = balance

    def show_balance(self):
        return self.__balance
```

## Exercise
Create a `BankAccount` class with a deposit and withdraw method.

## Challenge
Try adding a `__private` field and access it only through methods.

## Notes
Encapsulation helps protect data in larger systems.
