# Day 27: Forms, Routes, and Templates

## Goal
Learn how to accept input and render HTML pages.

## Example
```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')
```

## Exercise
Create a page with a form and a button.

## Challenge
Make the form accept a name and show it on the page.
