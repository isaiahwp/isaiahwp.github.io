---
title: Blog
layout: base.njk
---

## Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>
