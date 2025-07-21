---
layout: page
title: Home Page
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Resume
[View My Resume](/portfolio/assets/Kealan_Frost_Resume_Blank.pdf)

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}

## Contact
📧[name@domain.com](mailto:name@domain.com)  
📞[123-456-7890](tel:+11234567890)  
🔗[LinkedIn](https://www.linkedin.com/in/kealanfrost/)  
