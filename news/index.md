---
title: News
layout: single
header:
    overlay_filter: "0.5"
    overlay_image: /images/pages.jpg
    caption: "Photo by [Patrick Tomasso](https://unsplash.com/@impatrickt?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/pages?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)"
---

{: .student-list}

{% assign cur = '2101' %}
{% for pub in site.news reversed %}
{% capture year %}{{pub.date | date:'%Y'}}{% endcapture %}
{% if year != cur %}## {{year}} {% endif %}
{% assign cur = year %}
<li>
    <img src="{{ pub.picture }}" alt="Photo of a {{ pub.title | downcase }}" height= 200px>
    <a href="{{ pub.link }}">{{ pub.title }}</a>    
</li>
{% endfor %}

