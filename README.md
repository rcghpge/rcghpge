```mojo
from collections.list import List
from collections.string import String

fn about_me() raises -> String:
    """
    Generates an About Me in Mojo.
    """
    var name = "Robert"
    var profession = "Full-time University Student."
    var interests = List[String]()
    interests.append("Programming")
    interests.append("AI")
    interests.append("Data Science")
    var current_focus = "graduating"

    var about_me_text2 = String("Hey, I'm " + String(name) + ". I am a " + String(profession))
    about_me_text2 += ("\nMy interests include:\n")
    for i in range(len(interests)):
        var interest = interests[i]
        about_me_text2 += String("- ") + interest + "\n"
    about_me_text2 += ("Currently, I'm focusing on " + String(current_focus))
    return about_me_text2

fn main() raises:
    print(about_me())
```
