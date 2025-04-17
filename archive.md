---
layout: letter
title: "Archivo de Cartas"
permalink: /archive/
---

Aquí quedan registradas, para el juicio eterno (o al menos el algoritmo de búsqueda), todas las cartas escritas desde la sombra del Inti.

{% for post in site.posts %}
- <a href="{{ post.url }}">{{ post.title }}</a> <span style="color:#777;">({{ post.date | date: "%d/%m/%Y" }})</span>
{% endfor %}
