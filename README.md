<h2> Hi, I'm Fajrizky! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>

<p><em>
  Software Enginner <img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30">
</br>
  
</em></p>


[![Linkedin: fajrizky diputra](https://img.shields.io/badge/-fajrizkydiputra-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fajrizkydiputra/)](https://www.linkedin.com/in/fajrizkydiputra/)
[![GitHub Fajrizky](https://img.shields.io/github/followers/Fajrizky?label=follow&style=social)](https://github.com/Fajrizky)



```javascript
const fajrizky = {
  pronouns: "he" | "him",
  code: [PHP, Go, Javascript, Typescript, HTML, CSS, Python, Java],
  tools: [Laravel, Gin, Vue, Flutter, Express, Node, Figma, VCS],
  architecture: ["microservices", "event-driven", "design system pattern"],
}
```

​
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Arsenal:
    languages: tuple[str, ...] = ("Python", "JS", "Go")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "DynamoDB", "Redis")
    misc     : tuple[str, ...] = ("Docker", "Celery", "RabbitMQ", "Arq", "SQS")
    ongoing  : tuple[str, ...] = ("Django", "DRF", "Asyncio")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


arsenal = Arsenal()
print(arsenal.jsonify())
​



<img src="https://github-readme-stats.vercel.app/api?username=Fajrizky&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515">
