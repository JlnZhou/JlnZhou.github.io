---
layout: default
title: Blog
description: Bloguons!
---
# Articles

{% for post in site.posts %}
- ## <a href="{{ post.url }}">{{ post.title }}</a>
  ​    {{ post.excerpt }}
{% endfor %}

