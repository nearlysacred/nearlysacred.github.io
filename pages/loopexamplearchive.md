---
layout: page
show_meta: false
title: "Style your content!"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/category/"
---
<ul>
    {% for post in site.categories.sacredgeometry %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
