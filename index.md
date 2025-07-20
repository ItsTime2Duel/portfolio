---
layout: default
title: Kealan Frost
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
