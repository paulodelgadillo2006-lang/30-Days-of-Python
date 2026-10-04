# Day 19: APIs and Requests

## Goal
Learn how Python talks to the internet.

## Learn
Install `requests`:
```bash
pip install requests
```

Then:
```python
import requests

response = requests.get("https://api.github.com")
print(response.status_code)
print(response.json())
```

## Exercise
Request a public API and print a relevant field from the JSON response.

## Challenge
Use a weather API or GitHub API and display a meaningful result.

## Notes
APIs are a core skill in modern development.
