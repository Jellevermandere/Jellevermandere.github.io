---
layout: "page"
title: Visualisations
---

<h1> these are my visualisations: </h1>

{% for post in site.posts  %}

{% if post.categories contains "visualisations" %}

<h2> <a href= "{{ post.url }}" > {{ post.title }}</a> </h2> 

{% endif %}

{% endfor %}