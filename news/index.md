---
title: News
layout: splash
header:
    overlay_filter: "0.5"
    overlay_image: /images/pages.jpg
    caption: "Photo by [Patrick Tomasso](https://unsplash.com/@impatrickt?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/pages?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)"
---

<div class="grid-container">
{% assign cur = '2101' %}
{% for pub in site.news reversed %}
{% capture year %}{{pub.date | date:'%Y'}}{% endcapture %}
{% if year != cur %}## {{year}} {% endif %}
{% assign cur = year %}
     <div class="grid-item">
    <a href = "{{ pub.picture }}"> <img src="{{ pub.picture }}" alt="Photo of a {{ pub.title | downcase }}" style="float:left;width:160px;"> </a>
    <a href="{{ pub.link }}">{{ pub.title }}</a>    
    </div>
<br>
{% endfor %}

</div
