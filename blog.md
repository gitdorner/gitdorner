---
layout: default
title: Blog
permalink: /blog/
---

# Blog Posts

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*Published on {{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

[Read more]({{ post.url }})
{% endfor %}