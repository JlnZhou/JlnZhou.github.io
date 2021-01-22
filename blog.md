---
layout: default
title: Blog
description: nil
---
# Articles

{% for post in site.posts %}
- ## <a href="{{ post.url }}">{{ post.title }}</a>
  ​    {{ post.excerpt }}
{% endfor %}

