---
layout: home
---

# Welcome

- [About Me](/about.html)
- [Contact Info](/contact.html)
- [Technical Skills](/technical-skills.html)
- [Education](/education.html)
- [Project Blog](/)
- [Resume](/resume-2023.pdf)

## Projects
- [Neural Network in Excel](/projects/excel-neural-network.md)

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
