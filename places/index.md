---
layout: default
title: Places
---
# {{ page.title }}

{% for place in site.places %}
* [{{ place.name }}]({{ place.url }})
{% endfor %}
