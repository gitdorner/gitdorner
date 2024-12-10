---
layout: default
title: Home
---

# Welcome to My Tech Journey

## Recent Posts
{% for post in site.posts limit:3 %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}