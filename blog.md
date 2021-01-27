---
layout: default
title: Blog
description: Blig Blag Blog
---
# Articles

{% for post in site.posts %}
- ## <a href="{{ post.url }}">{{ post.title }}</a>
  ​    {{ post.excerpt }}
{% endfor %}

