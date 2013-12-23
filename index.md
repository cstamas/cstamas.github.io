---
layout: page
title: Welcome
tagline: My first attempt to use Jekyll
---

This is my private page for blog and other "static" content. Feel free to peek around.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

