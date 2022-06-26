---
layout: default
title: "Blog"
permalink: /blog/
---

{% for blog in site.categories.blogs %}
  {{ blog.output }}
{% endfor %}

