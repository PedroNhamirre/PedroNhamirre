> [!NOTE]
> **Pedro Nhamirre** — Learn. Code. Build.

<div align="center">


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedronhamirre)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://www.pedronhamirre.tech)

</div>

```python
# pedro_nhamirre.py
from __future__ import annotations
from dataclasses import dataclass
from typing import List

@dataclass
class TechStack:
    languages: List[str] = [
        "Java", "Python", "JavaScript", "TypeScript", "Golang"
    ]

    frameworks: List[str] = [
        "Spring Boot", "Django", "Next.js", "React",
        "Node.js", "Express.js"
    ]

    databases: List[str] = ["PostgreSQL", "MySQL", "MongoDB", "Firebase"]

    tools: List[str] = [
        "Docker", "Git", "Linux",
        "Swagger", "REST APIs"
    ]

@dataclass
class Developer:
    name: str = "Pedro Nhamirre"
    location: str = "🇲🇿 Mozambique"
    
    linkedin: str = "https://www.linkedin.com/in/pedronhamirre"
    website: str = "https://www.pedronhamirre.tech"
    email: str = "pedrooliv62@gmail.com"
    
    skills: TechStack = TechStack() 

me = Developer()
```
