---
title:  "PCISA3: USC Rosebowl Regatta (USSC)"
date:   2018-12-14 1:35:00 -0800
last_modified_at: 2018-12-29 20:40:00 -0800
modified_count: 3
#image for RSS (typically same URL as photo1 widget)
image: "https://lh3.googleusercontent.com/rCVyV_8LZ7LIlAned4g5AAF99QUSO5QsQahFvmyMB4KETp3DBHgXTEXyEsFwBINCsjqZ5iCbYpDTTh_YIlo6XmnsRKV-noyPOcJKlLXGsB6MvrwS1qIptTNq4J4nZv1Vr28VH-Kh5wpNi7SDA62IVrQxHzkf9rEALAkX6tkd7BEQ2u-rJmJuhFPL8jtWz8UtKAMc7w5K4tl3nkQom41a1qZMWhL0dstU2dn4QVs9AWKRZp7pT2xA-oHOMwcvmjbj34g81ici-xSezP5q4CjBK6HPS-Wedk61MC_zA0LF7Z81ioweLGbJ7gC09vyZm8PxYg01UHu1cxWLDxrZ4EseVCnpQzvrpC5dX4v69LdolBOQ_Jou0jhd8Mk8ad00wlCYsE6JQzdkn34CF94BCVWCJRsB1Ilf5KiY2Gup6TEXagvjWpkrldjyorCl4r2EAft5kQMJ6mClBsRYmsiaZ5wZZ4g9FyIt4TBjad3fLoSZPhWW4PsbM82H4hPeOqb0ktX0AnCj46A-2vgT2gCqPXnrIKnNGCYgaXUZj4FLbsNuBxdtuYK7lrCgIPBZWZ5Y6KW_voejsAzmxExGNYvDdfa7KJzcVcXNbr-9KTa8PGigHctcvOCrwqlPuMtaONDKK3-mWdBqa-IcyvjVvQh0jMtcVHSY05l2jpyX647apMvZFvQ20Ka8stbpUR-sKvUvaLd08jTn7tFtCuI5Z0zY9a0=w1675-h943-no"


photo1: 2018rosebowl1
photo2:

title_alert: "Rosebowl Information"

venue:  
  title: "US Sailing Center / Granada Beach"
  map:  "https://www.google.com/maps/place/United+States+Sailing+Center/@33.7518703,-118.1311972,17z/data=!3m1!4b1!4m5!3m4!1s0x80dd303c01d19acb:0x4a9f2f5df289c526!8m2!3d33.7518703!4d-118.1290085"
nor: "https://pcisa.hssailing.org/documents/2019-Rose-Bowl-NOR.pdf"
entrylist: "https://hssailing.org/machform/widget.php?key=90340xeb2ffe3c5d"
categories: [ 2018-19, PCISA ]

windfinder:
  title: LB Peninsula
  mapzoom: "#14"
  latitude: "33.7483"
  longitude: "-118.1240"
  unit_wave: "ft"
  unit_rain: "in"
  unit_temperature: "f"
  unit_wind: "mph" #kts
  days: 3
  show_day: 1
  location: long-beach-peninsula



signup-emoji: ":triangular_flag_on_post:"
signup: "https://docs.google.com/forms/d/e/1FAIpQLSePOXdW--1sn6oYcNezOHPHldTjDzAE-2wFDntbsxmvjt3scw/viewform"
---
{% assign photo1 = site.data.widget_photos[page.photo1] %}
{% assign photo2 = site.data.widget_photos[page.photo2] %}


{% if photo2 %}![{{ photo2.text }}]({{ photo2.url }})
**{{ photo2.text }}**
{% else %}
![{{ photo1.text }}]({{ photo1.url }})
**{{ photo1.text }}**  
{% endif %}

<div class="alert alert-info">
<h2>{{ page.title_alert }}</h2>
<br><h4>Special Practice Day</h4>
<p><strong>Reminder:</strong> Regatta sailors have a special Team practice on Friday 1/4/19 from ~11:30a (boats launched by 12p), team will practice, leave boats at Granada beach prepped for regatta and back to ABYC by 5:00p</p>
<br><h4>Rosebowl Information</h4>
<p>USC Rosebowl is hosted by US Sailing Center (USSC) in Long Beach. It's the only opportunity of the season for High School teams to sail with college teams, and its on <a href="{{ page.venue.map }}">Granada Beach near {{ page.venue.title }}</a></p>
</div>  

#### Dinner & College Presentations

**Dinner:** Sailors have a total of four dinner tickets as part of registration, _not enough for parents or even **all** sailors._ [:ticket:  Additional dinner tickets](https://hssailing.org/machform/view.php?id=34883) (includes college presentations) must be purchased by Dec 31 and are $15 ea. _Highly recommended!_  

**College Presentations:** There will be a short presentation on Intercollegiate Sailing following dinner on Saturday night. Students and parents interested in information about college sailing in general, or specific collegiate programs should plan to attend. All colleges should plan to be represented. Please read the 2019 Rose Bowl Regatta Important Information document for more details on the dinner.

**t-shirts:** Based on past, I also purchased four t-shirts. I assumed two small shirts for Nikhil, Elissa, and a med or large for Diego and likely another person (Diego & others can workout sizes for med-large). [:tshirt: Additional shirts](https://hssailing.org/machform/view.php?id=34883) can be purchased at a discount using same link as dinner, or for $20 at the Regatta.

### Schedule of Events

<!--more-->
Please plan to arrive to [{{ page.venue.title }}]({{ page.venue.map }}) by 8:55a. Last year breakfast burritos were available at the beach hut on Saturday (and Sunday?); likely the the same this year. :dollar: CASH ONLY :dollar:

#### Saturday

-  0850                   Meetup  
-  0900                   Boat inspection and Team Check-In  
-  1030                   Competitors’ Meeting  
-  1100                   First Warning  
-  NO CUT OFF TIME  
-  1700                   Dinner & College Sailing Forum

#### Sunday

-  0900                   Meetup  
-  0930                   PCISA Meeting
-  1030                   Skippers Meeting
-  1530                   No Starts After  
-  1700                   Trophy Presentations

### Weather Info for {{ page.title }}
- <a href="https://www.windfinder.com/windstatistics/{{ page.windfinder.location }}">Wind: {{ page.windfinder.title }}</a>
- <a href="https://www.windfinder.com/forecast/{{ page.windfinder.location }}">Forecast: {{ page.windfinder.title }}</a>



### Scoring & Rotations


Regatta Results and Rotations can be found at:

-   Techscore without an account at: [https://scores.hssailing.org](https://scores.hssailing.org)
-   Sato will be sailing in Bronze fleet:  [https://scores.hssailing.org/s19/rosebowl-bronze/](https://scores.hssailing.org/s19/rosebowl-bronze/)
-   Rotations: [https://scores.hssailing.org/s19/rosebowl-bronze/rotations/](https://scores.hssailing.org/s19/rosebowl-bronze/rotations/)

### Wind & Weather


#### Windfinder: {{ title_alert }}

<a href="https://www.windfinder.com/forecast/{{ page.windfinder.location }}">Forecast: {{ page.windfinder.title }}</a>

<script type="text/javascript" src="https://www.windfinder.com/widget/forecast/js/{{page.windfinder.location}}?unit_wave={{page.windfinder.unit_wave}}&unit_rain={{page.windfinder.unit_rain}}&unit_temperature={{page.windfinder.unit_temperature}}&unit_wind={{page.windfinder.unit_wind}}&days={{page.windfinder.days}}&show_day={{page.windfinder.show_day}}"></script>

<noscript><a rel='nofollow' href='https://www.windfinder.com/forecast/{{page.windfinder.location}}?utm_source=forecast&utm_medium=web&utm_campaign=homepageweather&utm_content=noscript-forecast'>Wind forecast for undefined</a> provided by <a rel='nofollow' href='https://www.windfinder.com?utm_source=forecast&utm_medium=web&utm_campaign=homepageweather&utm_content=noscript-logo'>windfinder.com</a></noscript>


#### Willy Weather

<div><iframe style="display: block;" src="https://cdnres.willyweather.com/widget/loadView.html?id=99297" width="700" height="520" frameborder="0"  scrolling="no"></iframe><a style="display: block;position: relative;height: 20px;margin: -20px 0 0 0;text-indent: -9999em;z-index: 1" href="https://swell.willyweather.com/ca/los-angeles-county/long-beach.html" rel="nofollow">https://swell.willyweather.com/ca/los-angeles-county/long-beach.html</a></div>

[View on website](https://swell.willyweather.com/ca/los-angeles-county/long-beach.html)

![{{ photo1.text }}]({{ photo1.url }})
**{{ photo1.text }}**
