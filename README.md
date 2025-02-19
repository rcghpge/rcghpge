# About Me
```python
def about_me() -> str:
    """
    Generate an About Me in Python.
    """
    name = "Robert"
    profession = "full-time university student."
    interests = [
        "Research",
        "Development",
        "Programming",
        "Engineering",
        "AI",
        "Data Science"
    ]
    current_focus = "graduating."

    about_me_text = f"Hey, I'm {name}. I am a {profession}\n"
    about_me_text += "My interests include:\n"
    for interest in interests:
        about_me_text += f"- {interest}\n"
    about_me_text += f"Currently, I'm focusing on {current_focus}"

    return about_me_text

if __name__ == "__main__":
    print(about_me())
```
TLDR: I'm Robert - MySpace taught me how to code
