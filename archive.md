---
title: Archives
permalink: /archive/
photo1: treasureisland1
published: true
---
{% assign photo1 = site.data.widget_photos[page.photo1] %}

![{{ photo1.text }}]({{ photo1.url }})


{% include data/widget_archive.html %}
