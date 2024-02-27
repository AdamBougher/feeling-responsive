---
layout: page
show_meta: false
title: "Meet our Team!"
subheadline: "The People who make 71North what it is!"
header:
   image_fullwidth: "gallery-example-1.jpg"
permalink: "/Team/"
---
<ul>
    {% for post in site.categories.TeamMember %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>