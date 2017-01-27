---
layout: page
show_meta: false
title: "Beceri Sınıfı Şampiyonlar"
subheadline: "Marvel's Contest of Champions"
header:
   image_fullwidth: "/other/beceri-banner.jpg"
permalink: "/beceri/"
---
<ul>
    {% for post in site.categories.beceri %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
