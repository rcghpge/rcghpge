# About Me
```python
"""
Generate an About Me in Python
"""
def about_me() -> str:
    return "Hey, I'm Robert. I am a full-time university student.\nMy interests include:\n" + "\n".join(
        "- " + i for i in ["Research", "Development", "Programming", "Engineering", "AI", "Data Science"]
    ) + "\nCurrently, I'm focusing on graduating."

print(about_me())
```
TLDR: I'm Robert - MySpace taught me how to code
