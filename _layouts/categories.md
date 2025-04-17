---
layout: letter
title: "Todas las Categorías"
permalink: /categories/
---

{% for category in site.categories %}
- <a href="/categories/{{ category[0] }}/">{{ category[0] }}</a> ({{ category[1].size }})
{% endfor %}
