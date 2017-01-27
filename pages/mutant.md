---
layout: page
show_meta: false
title: "Mutant Sınıfı Şampiyonlar"
subheadline: "Marvel's Contest of Champions"
header:
   image_fullwidth: "/other/mutant-banner.jpg"
permalink: "/mutant/"
---
<ul>
    {% for post in site.categories.mutant %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
