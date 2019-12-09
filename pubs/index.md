---
title: Publications
layout: single
---

{% for pub in site.pubs %}
{{pub.excerpt | replace: "#", pub.url }}
{% endfor %}