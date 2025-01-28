# About Me
Generate an About Me for your GitHub page and also run your first line of code in Mojo 🔥
```mojo
from collections import list, string

fn about_me() raises -> String:
    """
    Generate an About Me in Mojo.
    """
    var name = "Robert"
    var profession = "full-time university student."
    var interests = List[String]()
    interests.append("Research")
    interests.append("Development")
    interests.append("Programming")
    interests.append("Engineering")
    interests.append("AI")
    interests.append("Data Science")
    var current_focus = "graduating."

    var about_me_text = String("Hey, I'm " + String(name) + ". I am a " + String(profession))
    about_me_text += ("\nMy interests include:\n")
    for i in range(len(interests)):
        var interest = interests[i]
        about_me_text += String("- ") + interest + "\n"
    about_me_text += ("Currently, I'm focusing on " + String(current_focus))
    return about_me_text

fn main() raises:
    print(about_me())
```
TLDR: I'm Robert - this is my GitHub page to share programming knowledge with the open source comminity.
