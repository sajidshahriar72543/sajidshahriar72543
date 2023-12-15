<p align="center">
  <img src="https://github.com/sajidshahriar72543/sajidshahriar72543/blob/main/glitch.gif"/>
</p>

## Hi! I am <a href="https://sajidshahriar72543.github.io">**Sajid**
<p><em>A bachelor student at <a href="https://ruet.ac.bd">Rajshahi University of Engineering and Technology</a>, in Electrical and Computer Engineering.</br>
</em></p>


```python
class AboutMe:
    def __init__(self):
        self.pronouns = ["he", "him"]
        self.code = ["C", "C++", "Dart", "Python", "Bash", "Java"]
        self.front_end = ["Flutter"]
        self.back_end = ["Firestore", "Firebase"]
        self.mobile = ["Android"]
        self.current_occupation = ["4th year student", "open for part-time job opportunities [remote]"]
        self.on_going_projects = ["PixelOS-AOSP", "FusionOS"]
        self.challenge = "working on myself to become better everyday"

    def display_info(self):
        print(f"Pronouns: {', '.join(self.pronouns)}")
        print(f"Code: {', '.join(self.code)}")
        print("Technologies:")
        print(f"   FrontEnd: {', '.join(self.front_end)}")
        print(f"   BackEnd: {', '.join(self.back_end)}")
        print(f"   Mobile: {', '.join(self.mobile)}")
        print(f"Current Occupation: {', '.join(self.current_occupation)}")
        print(f"On Going Projects: {', '.join(self.on_going_projects)}")
        print(f"Challenge: {self.challenge}")

about_me = AboutMe()
about_me.display_info()
```
