---
layout: default
title: People
---
# {{ page.title }}

<ul class="people">
  {% for post in people %}
    <li><span>{{ post.title }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
