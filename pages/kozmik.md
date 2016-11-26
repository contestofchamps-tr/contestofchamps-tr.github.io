---
layout: page
show_meta: false
title: "Kozmik Sınıfı Şampiyonlar"
subheadline: "Marvel's Contest of Champions"
header:
   image_fullwidth: "/other/kozmik-banner.jpg"
permalink: "/kozmik/"
---
<ul>
    {% for post in site.categories.kozmik %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
