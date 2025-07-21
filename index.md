---
layout: page
title: Home Page
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Resume
[View My Resume](/portfolio/assets/Kealan_Frost_Resume_Blank.pdf)

## Projects

<div style="display: flex; flex-direction: column; gap: 1.Sem;">

{% for project in site.projects %}
  <div style="display: flex; align-items: center;">
    <img src="{{ project.thumbnail }}" alt="{{ project.title }} thumbnail" width="100" style="margin-right: 15px;">
    <a href="{{ site.baseurl }}{{ project.url }}">{{ project.title }}</a>
  </div>
{% endfor %}

</div>

## Contact Me
📧 [name@domain.com](mailto:name@domain.com)  
📞 [123-456-7890](tel:+11234567890)  
🔗 [LinkedIn](https://www.linkedin.com/in/kealanfrost/)  
