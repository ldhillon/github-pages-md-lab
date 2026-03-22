---
layout: home
title: Home
permalink: /
---

# Welcome


This site is deployed using **GitHub Pages**.

All pages are written in **Markdown** and automatically converted to HTML.

## Navigation

[About](about/)
[Documentation](docs/)

---

## Example Content

Here is some Markdown formatting.

### Code Example
```bash
kubectl get pods

```

### Python code example

```python
import re

def find_words_with_alphabets_and_numbers(input_string):
    pattern = r'\b(?=\w*\d)(?=\w*[a-zA-Z])\w+\b'
    # Find all matches
    matches = re.findall(pattern, input_string)
    return matches

# Example usage
input_string = "Hello world123, this is a test string with 12345 and test1ng."
print(find_words_with_alphabets_and_numbers(input_string))
```
