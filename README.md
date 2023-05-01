```python
class Nobitha:
    def __init__(self, age, nationality, religion, relationship_status, skills, languages, contact):
        self.name = "Nobitha"
        self.age = age
        self.nationality = nationality
        self.religion = religion
        self.relationship_status = relationship_status
        self.skills = skills
        self.languages = languages
        self.contact = contact
    
    def greet(self):
        return f"Hello, I'm {self.name}! Nice to meet you. 😊"

nobitha = Nobitha(age='19+', nationality='Indian 🇮🇳', religion='Hindu 🥀', relationship_status='with you 💖', 
                  skills=['Python', 'HTML', 'CSS', 'UI/UX design'], languages=['Telugu', 'English', 'Hindi'], 
                  contact='+919876543210 😔')
print(nobitha.greet())  ## Output: Hello, I'm Nobitha! Nice to meet you. 😊
```
