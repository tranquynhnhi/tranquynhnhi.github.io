---
layout: page
title: "Hobby"
subheadline: ""
teaser: "Here are something I spend my leisure time on."
header:
   image_fullwidth: "header_roadmap_3.jpg"
permalink: "/hobby/"
---
<ul>
{% for post in site.categories.hobby %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>