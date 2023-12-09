```py
import github
import random
from github import read_me

class aboutMe():
    def __init__(self):
        self.contacts = [
            'Discord: equ.ty',
            'Telegram: t.me/elixades' #Slow Response
            ]
        print(random.choice(self.contacts))

        self.languages = [
            'Python'
            ]
        self.learning = [
            'Javascript'
            'GoLang'
            ]
        for lang in self.languages:
            print(lang)
        
    
if __name__ == "__main__":
    aboutMe()
```
