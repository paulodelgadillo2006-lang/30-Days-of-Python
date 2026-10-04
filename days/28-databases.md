# Day 28: Intro to Databases

## Goal
Understand how apps store data.

## learn
Common database types:
- SQLite
- PostgreSQL
- MySQL

Example with SQLite:
```python
import sqlite3

conn = sqlite3.connect('data.db')
cur = conn.cursor()
cur.execute('CREATE TABLE IF NOT EXISTS users (id INTEGER PRIMARY KEY, name TEXT)')
conn.commit()
```

## Exercise
Create a small database and insert one record.

## Challenge
Build a notes table and display all notes.
