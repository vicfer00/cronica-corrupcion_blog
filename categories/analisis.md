---
layout: letter
title: "Analisis"
permalink: /categories/analisis/
---

{% assign category_name = 'analisis' %}
{% for post in site.posts %}
  {% if post.categories contains category_name %}
- <a href="{{ post.url }}">{{ post.title }}</a> <span style="color:#777;">({{ post.date | date: "%d/%m/%Y" }})</span>
  {% endif %}
{% endfor %}
