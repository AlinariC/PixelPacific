---
layout: default
title: "Authors"
permalink: /authors/
---

# Our Authors

{% for author in site.authors %}
- [{{ author.name }}]({{ author.url }})
{% endfor %}
