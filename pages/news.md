---
layout: page
show_meta: false
title: "News"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/news/"
---
<ul>
    {% for post in site.categories.news %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

