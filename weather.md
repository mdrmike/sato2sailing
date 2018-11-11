---
title: Weather near ABYC
permalink: /weather/
#photo1:
published: true
---
{% assign photo1 = site.data.widget_photos[page.photo1] %}

![{{ photo1.text }}]({{ photo1.url }})


{% include willyweather.html title="Willy Weather" intro="Note dropdown allows you to quickly view other common High School regatta venues. Also, you can quickly check Wind, Weather, and UV." %}
{% include windfinder.html intro="This wind, rain, is forecast for LB Peninsula near ABYC." %}
