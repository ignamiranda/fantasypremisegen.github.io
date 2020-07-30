---
layout: default
title: People
---
# {{ page.title }}
test2

{% for person in site.people %}
* [{{ person.name }}]({{ person.url }})
{% endfor %}
