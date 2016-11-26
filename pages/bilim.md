---
layout: page
show_meta: false
title: "Bilim Sınıfı Şampiyonlar"
subheadline: "Marvel's Contest of Champions"
header:
   image_fullwidth: "/other/bilim-banner.jpg"
permalink: "/bilim/"
---
<ul>
    {% for post in site.categories.bilim %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
