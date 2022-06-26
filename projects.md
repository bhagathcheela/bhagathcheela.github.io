---
layout: page
title: Projects
permalink: /projects
---

{% for project in site.categories.projects %}
  {{ project.output }}
{% endfor %}
