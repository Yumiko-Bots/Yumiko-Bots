## <u>Python</u>
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

## <u>Go</u>
```go
package main

import "fmt"

type Nobitha struct {
    name string
    age string
    nationality string
    religion string
    relationship_status string
    skills []string
    languages []string
    contact string
}

func (n Nobitha) greet() string {
    return fmt.Sprintf("Hello, I'm %v! Nice to meet you. 😊", n.name)
}

func main() {
    nobitha := Nobitha{
        name: "Nobitha",
        age: "19+",
        nationality: "Indian 🇮🇳",
        religion: "Hindu 🥀",
        relationship_status: "with you 💖",
        skills: []string{"Python", "HTML", "CSS", "UI/UX design"},
        languages: []string{"Telugu", "English", "Hindi"},
        contact: "+919876543210 😔",
    }
    fmt.Println(nobitha.greet())  // Output: "Hello, I'm Nobitha! Nice to meet you. 😊"
}
```

## <u>C lang</u>
```c
#include <stdio.h>

typedef struct {
    char* name;
    char* age;
    char* nationality;
    char* religion;
    char* relationship_status;
    char** skills;
    char** languages;
    char* contact;
} Nobitha;

void greet(Nobitha* n) {
    printf("Hello, I'm %s! Nice to meet you. 😊\n", n->name);
}

int main() {
    char* skills[] = {"Python", "HTML", "CSS", "UI/UX design"};
    char* languages[] = {"Telugu", "English", "Hindi"};

    Nobitha nobitha = {
        .name = "Nobitha",
        .age = "19+",
        .nationality = "Indian 🇮🇳",
        .religion = "Hindu 🥀",
        .relationship_status = "with you 💖",
        .skills = skills,
        .languages = languages,
        .contact = "+919876543210 😔",
    };

    greet(&nobitha);  // Output: "Hello, I'm Nobitha! Nice to meet you. 😊"

    return 0;
}
```
