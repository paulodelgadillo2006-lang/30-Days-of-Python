# Day 26: Web Basics with Flask

## Goal
Create a small web app.

## Install
```bash
pip install flask
```

## Example
```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hello from Flask!"
```

## Exercise
Create a homepage that prints a welcome message.

## Challenge
Add a second route like `/about`.
