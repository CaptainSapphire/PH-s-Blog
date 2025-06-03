---
layout: default
title: "Home"
---

Welcome to my blog! Here are my latest posts:
{% raw %}
<ul class="post-previews">
  {% for post in site.posts limit:5 %}
    <li class="post-preview">
      <a href="{{ post.url | relative_url }}">
        {% if post.featured-img %}
          <img src="{{ post.featured-img | relative_url }}" alt="{{ post.title }} featured image" class="post-thumbnail">
        {% endif %}
        <h2>{{ post.title }}</h2>
      </a>
    </li>
  {% endfor %}
</ul>
{% endraw %}
{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
