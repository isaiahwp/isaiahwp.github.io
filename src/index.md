---
title: Welcome
layout: base.njk
---

Blog about programming, video games, algorithms, things that interests me.

## Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>
