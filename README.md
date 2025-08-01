<img align="right" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Farcangelofranco&label=--%20visitors&labelColor=%23697689&countColor=%23555555&style=flat-square&labelStyle=lower"/>

<h1 align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Consolas&pause=1000&color=6B8095&center=true&vCenter=true&multiline=true&repeat=false&random=false&width=435&height=100&lines=Greetings!+;My+name+is+Arcangelo+Franco." alt="Typing SVG" /></a>
</h1>
<br/>

  ```python
 class Education:
    def __init__(self):
        self.bachelor_university = "University of Pisa"
        self.bachelor_field = "Digital Humanities"
        self.master_university = "University of Pisa"
        self.master_field = "NLP & Digital Humanities"
        self.research_interests = [
            "Machine Learning",
            "Natural Language Processing",
            "Artificial intelligence",
            "Data Science"
        ]

    def describe(self):
        interests = ", ".join(self.research_interests)
        return (
            f"I completed my Bachelor's degree in {self.bachelor_field} at {self.bachelor_university},\n"
            "focusing on topics such as Natural Language Processing, Human Language Technologies,\n"
            "Web Development, and Data Analysis.\n"
            f"I'm currently pursuing my Master's degree in {self.master_field} at {self.master_university}.\n"
            f"My research interests include {interests}."
        )

class Introducer:
    def __init__(self):
        self.name = "Arcangelo"
        self.surname = "Franco"
        self.age = 29
        self.location = "Italy"
        self.education = Education()

    def introduce(self):
        return (
            f"Hi! My name is {self.name} {self.surname}.\n"
            f"I'm {self.age} years old and I'm from {self.location}.\n"
            "I hope I can be of help to you."
        )

    def describe_education(self):
        return self.education.describe()

def main():
    presenter = Introducer()
    print(presenter.introduce())
    print()
    print(presenter.describe_education())

if __name__ == "__main__":
    main()
  ```
    

<!--
**arcangelofranco/arcangelofranco** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
