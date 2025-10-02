---
layout: default
title: "Projects"
permalink: /projects
---
# 🚀 Projects

{% for repo in site.data.projects %}
- [{{ repo.name }}]({{ repo.url }}) – {{ repo.description }}
{% endfor %}