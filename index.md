---
layout: default
title: This_Is_The_Website_Title_In_The_Index_File
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Resume
[View My Resume](Kealan_Frost_Resume.pdf)

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}
