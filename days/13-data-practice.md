# Day 13: More Practice with Data

## Goal
Use lists, dictionaries, loops, and conditionals together.

## Exercise
```python
students = [
    {"name": "Ana", "score": 90},
    {"name": "Pedro", "score": 70},
    {"name": "Mia", "score": 60}
]

for student in students:
    if student["score"] >= 75:
        print(student["name"], "passed")
    else:
        print(student["name"], "needs more work")
```

## Challenge
Write a script that reads a list of tasks and prints only the incomplete ones.

## Notes
This is the kind of logic used in apps, dashboards, and automation tools.
