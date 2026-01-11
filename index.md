---
layout: default
---

# Welcome

- [About Me](/about.html)
- [Contact Info](/contact.html)
- [Technical Skills](/technical-skills.html)
- [Education](/education.html)
- [Project Blog](/)
- [Resume](/resume-2023.pdf)

## Projects
{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
