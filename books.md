---
layout: default
title: "Books"
permalink: /books/
---

# Our Books

{% for book in site.books %}
## [{{ book.title }}]({{ book.url }})
by {{ book.author }}

{{ book.description }}

[View Website]({{ book.website }}) | [Buy on Amazon]({{ book.amazon }})

---
{% endfor %}
