---
layout: page
title: Blog
permalink: /blog/
---

Welcome to my blog! Here you'll find all my latest posts on science, philosophy, and other interesting topics.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
  {{ post.excerpt }}
{% endfor %}