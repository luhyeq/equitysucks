```py
import github
import random
from github import read_me

class aboutMe():
    def __init__(self):
        self.contacts = [
            'Discord: equity#0001',
            'Telegram: t.me/secluding'
            ]
        print(random.choice(self.contacts))

        self.languages = [
            'Python',
            'HTML', 'CSS', 'Javascript'
            ]
        for lang in self.languages:
            print(lang)
        
    
if __name__ == "__main__":
    aboutMe()
```
