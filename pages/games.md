---
layout: "page"
title: Games
---

<h1> these are my games: </h1>

{% for post in site.posts  %}

{% if post.categories contains "games" %}

<h2> <a href= "{{ post.url }}" > {{ post.title }}</a> </h2> 

{% endif %}

{% endfor %}
