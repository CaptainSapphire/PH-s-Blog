---
layout: default
title: "Home"
---

# Latest Posts
<ul class="post-previews">
  {% for post in site.posts limit:5 %}
    <li class="post-preview">
      <a href="{{ post.url | relative_url }}">
        {% if post.featured-img %}
          <img src="{{ post.featured-img | relative_url }}" alt="{{ post.title }} image" class="post-thumbnail">
        {% endif %}
        <h2>{{ post.title }}</h2>
      </a>
    </li>
  {% endfor %}
</ul>

Welcome to my blog! Here are my all my posts:
{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
