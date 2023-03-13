```py
from random import choice

class desc():
    def __init__(self):
    	self.contact = ['kh#1337', 't.me/clucked', 'software@fbi.ac']
        self.desc = f'''
	   I'm khai a self taught developer.
           I am interested in Cyber Secuirity (Ethical Hacking), Artifical Intelligence & API Exploitation.
	   Feel free to contact me through {choice(self.contact)}
        '''
	
	self.age = 13
	self.net_worth = "$800.00+"
	self.sports = "Basketball, Track, Swimming"
	self.hireable = True
	
        self.os = 'Windows 10 Pro'
        self.ram = '8 GB'
        self.cpu = 'Intel Core i3'
	
        self.languages = ['Python', 'HTML', 'CSS', 'Javascript']
	self.cloud_plats = ['Heroku', 'Netlify']
	self.database = ['MongoDB', 'SQLite']
        self.learning = 'Golang, SQLite, Javascript', 'More Python', 'Full Stack Web Development'
	self.in_development = "District Selfbot"
	
	
if __name__ == "__main__":
    desc()
```
