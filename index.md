---
layout: home
title: Home Page
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Resume
[View My Resume](/portfolio/assets/Kealan_Frost_Resume.pdf)

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}
