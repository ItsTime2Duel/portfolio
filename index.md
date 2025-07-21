---
layout: page
title: Home Page
---

# Kealan Frost

Welcome to my engineering portfolio. I'm an Electrical Engineering student passionate about semiconductors, embedded systems, and quantum photonics.

## Resume
[View My Resume](/portfolio/assets/Kealan_Frost_Resume_Blank.pdf)

## Projects

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2em;">

{% for project in site.projects %}
  <div style="border: 1px solid #ccc; padding: 1em; border-radius: 10px; background: #f9f9f9;">
    <img src="{{ project.thumbnail }}" alt="{{ project.title }} thumbnail" style="width: 100%; border-radius: 8px;">
    <h3 style="margin-top: 0.8em;">{{ project.title }}</h3>
    <p>{{ project.description }}</p>
    <a href="{{ site.baseurl }}{{ project.url }}">Learn more</a>
  </div>
{% endfor %}

</div>

## Contact Me
📧 [name@domain.com](mailto:name@domain.com)  
📞 [123-456-7890](tel:+11234567890)  
🔗 [LinkedIn](https://www.linkedin.com/in/kealanfrost/)  
