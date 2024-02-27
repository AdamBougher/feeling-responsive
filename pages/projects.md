---
layout: page
show_meta: false
title: "Projects:"
subheadline: "Some of the projects we have going on around the studio"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/Projects/"
---
<ul>
    {% for post in site.categories.project %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>