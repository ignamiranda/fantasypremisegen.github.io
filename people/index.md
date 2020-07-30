---
layout: default
title: Thorlacuin D&D Wiki
---
# {{ page.title }}

<p class="meta">{{ page.date | date_to_string }}</p>

<ul class="posts">
  {% for post in site.people %}
    <li><span>{{ post.title }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
