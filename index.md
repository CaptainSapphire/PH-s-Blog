---
layout: default
title: "Home"
---

Welcome to my blog! Here are my latest posts:
{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
