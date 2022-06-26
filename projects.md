---
layout: page
title: Projects
permalink: /projects/
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% for project in site.categories.projects %}
    {{ project.output }}
  {% endfor %}
{% endif %}
