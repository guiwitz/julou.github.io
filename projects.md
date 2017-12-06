---
layout: page
title: Projects
# navigation_weight: -7
---


{% for project in site.projects reversed %}
{% if project.published %}
  <h2>{{ project.title }}</h2>
  <p><i>with {{ project.collaborators }}.</i></p>
  <p>{{ project.content }}</p>
<!--  <p><a href="{{ project.url }}">{{ project.title }}</a></p> -->
{% endif  %}
{% endfor %}
