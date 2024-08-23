```python
import random

class Me:
    def __init__(self):
        self.greeting = "Yeet! 👋, I'm Zihaan"
        self.bio = "Software engineer from Maldives"
        self.languages = ['javascript', 'typescript', 'python']
        self.frameworks = ['NextJS', 'React']
        self.website = 'dev.idhaan.me'
        self.projects = ['https://donors.ungoodhoo.live']
        self.facts = [
            "I love Telegram.",
            "Not only do I love Telegram, I obsess over it.",
        ]

    def get_random_fact(self) -> str:
        """Get a random fact about me."""
        return random.choice(self.facts)



if __name__ == "__main__":
    me = Me()
    print(me.get_random_fact())

```