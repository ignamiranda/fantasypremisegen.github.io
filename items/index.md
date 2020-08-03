---
layout: default
title: Items
---
# {{ page.title }}

{% for item in site.items %}
* [{{ item.name }}]({{ item.url }})
{% endfor %}