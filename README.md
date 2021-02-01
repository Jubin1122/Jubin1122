

```python
class DataEngineer:
    def __init__(self):
        self.name = "Jubin Mohanty"
        self.role = "Data Engineer"
        self.location = "28.6139° N, 77.2090° E"
        self.blog = ""
        self.knowledge_base = [
            "Software Enginnering",
            "Machine Learning",
            "Deep Learning",
            "Backend Development",
        ]
        self.knowledge_base.insert(0, "Cloud Devops")

    def say_hi(self):
        print(
            """Hello my friend, thanks for dropping by!

This is {name}, I live in {location}. I work as a {role} and recently I am focusing on {focus} for my personal growth.

I have wide interests, but most of them are {knowledge_base}.

I write down tips and lecture notes on my personal tech blog, which can be found here: {blog}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,
            )
        )


me = DataEngineer()
me.say_hi()
```




- 🔭 I’m currently working on Machine Learning Pipelines using TensorFlow
- 🌱 I’m currently learning AWS Cloud Automation using boto3
- 👯 I’m looking to collaborate on Opensource Projects
- 🤔 I’m looking for help with Front-End Projects
- 💬 Ask me about Backend, Data Enginnering, and Pythonic Hacks
- 📫 How to reach me: 
- 😄 Pronouns: He/Him
- ⚡ Fun fact: Lot of them!!

