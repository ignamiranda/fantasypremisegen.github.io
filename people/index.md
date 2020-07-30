---
layout: default
title: People
---
# {{ page.title }}

{% for person in site.people %}
* [{{ person.name }}]({{ person.url }})
{% endfor %}
