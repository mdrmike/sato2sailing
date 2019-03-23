---
title:  "SoCal5: SDYC—Regatta in San Diego"
date:   2019-03-22 23:00:00 -0700
last_modified_at: 2019-03-22 23:00:00 -0700
modified_count: 0
categories: [ 2018-19, socal ]
image: "https://lh3.googleusercontent.com/BWb24EWIGTruZSRr8BXpq5biPJHrUFFAJWyjIEKaSx9Te9GmMibaH9eT8ynQprN7CGEAYhDbQYaCkyOd_jEqrggB4PBxoUYl_41gjmfiSLXWNmq-9cj-yoIFAeboO3cB3XU8EA8rrSqK05mLux1-dkzuAQQ1gJ90kVzM64QbwxSBm5LWQCTZZ6h-rI9y2mlmRCTLnxS5DI5pGI-hqppfqdNzYnWrvuBTo_1R0ArdbVtsB7JypU_YcslMIEvh6Xo1CKrY0NhVI7RaecJAPISVivXo4yFglCDzdkIYEORvMVegcxxgIvy1j8HUsScKp3OIPKWUPTV4HTzo8MFgCrVmiBSS3A3ilnWLuJHTbr1A4JNdflZnntCVlEYRE07eZvz7icZtoJ1mPsgsbun5ofLyhEWjmgy1ovn2dkia8rhKgLejH5goOxj5VGLIjitYmHrxOA0tLPqym7MrDhnT6WZGUdX-KSDZi7ETpqH1kLo98WUqlM1t_e1QAfN-WQsgS3A_tLZJRTK-K4mdtY0mXkVaIkiYskCGmOdDY-KB2bMNkbg3TXznH4Sa1rtqW2UAUfuI1t1UF4KHig-CqOgUoxfMz4etiY_sPItDz8isHWcPrbWsno7yAxgEn-WHdoZgvWWbzw3mmKxywnFK1Cy7exsXWSjLmkVQSe4kS54egNQMvgEcWZLBBi4Gn9rKDTzpjm_9wdwCS0flAcJEqhUjWL-tb8sxyA=w1675-h942-no"

photo1: 2018socal5a
photo2:

signup-emoji: ":triangular_flag_on_post:"
signup: "https://docs.google.com/forms/d/e/1FAIpQLSePOXdW--1sn6oYcNezOHPHldTjDzAE-2wFDntbsxmvjt3scw/viewform"
venue:  
  title: "SDYC"
  map:  "https://www.google.com/maps/place/San+Diego+Yacht+Club/@32.7188308,-117.2383353,15z/data=!4m5!3m4!1s0x80deab9883524577:0xb32271e0380bbf75!8m2!3d32.7188262!4d-117.2295806"
nor: "https://hssailing.org/schedule_news/docs/pcisa_docs/2018-2019-PCISA-SoCal-NOR.pdf"
entrylist: "https://hssailing.org/machform/widget.php?key=108308xeb2ffe3c5d"

windfinder:
  unit_wave: "ft"
  unit_rain: "in"
  unit_temperature: "f"
  unit_wind: "mph" #kts
  days: 3
  show_day: 1
  location: san-diego_shelter-island


---

{% assign photo1 = site.data.widget_photos[page.photo1] %}
{% assign photo2 = site.data.widget_photos[page.photo2] %}


{% if photo2 %}![{{ photo2.text }}]({{ photo2.url }})
**{{ photo2.text }}**
{% else %}
![{{ photo1.text }}]({{ photo1.url }})
**{{ photo1.text }}**
{% endif %}
<div class="alert alert-info" markdown="1">
### Information

- [{{ page.signup-emoji }} All Sailors Please Register (even if you're not going)]({{ page.signup }})
- :information_source: SoCal5 is in San Diego.
- :calendar: Please plan to arrive at <a href="{{page.venue.map}}" target="_blank">:round_pushpin: {{page.venue.maptitle}}</a> by 8:45a.
- :hamburger: :watermelon: :potable_water: Bring Food/snacks for keeping on boats! Sailors will be on water from 1030a - 530p
</div>


## Schedule

<div class="alert alert-warning" markdown="1">
**Parents:**  Sailors need to be onsite by 8:45a. Boat setup and registration is from 9-10a. Warning for first gold race is at 11a (silver shortly after).  Final race must start by 5p on Sat (and by 4p on Sun). If winds are good, they'll likely end sooner. All details are in NOR. (see links in sidebar)
</div>

-  0845 [Meetup at SDYC]({{page.venue.map}})
-  0900 Boat check-in
<!--more-->
-  1000 Onsite registration closes
-  1000 Competitor's meeting and Coaches Meeting
-  1100 First Warning
-  1600 Deadline for Starting Last Race
-  1700 Awards (or soon as possible after racing)  

### Regatta Information  

Sato is sending three boats.

1.  Gold1: Nikhil Stewart + Elissa Martinez
1.  Silver1: Troy Davidson + Libby Loveridge
1.  Silver2: Diego Lockyer + Tyler Hoang


## Wind & Weather Forecasts

**Sun March 3:** Forecast is cold, but mostly sunny, with chance of rain on Sunday. The biggest changes appear to be changes in tide direction each day, and wave frequency (half speed on Sunday).

[![Weather forecast](/assets/images/posts/2019/SDYC-forecast2--2019-03-23-24.png) _Click for weather current updates from windfinder.com_](https://www.windfinder.com/forecast/san-diego_shelter-island)

[![Weather forecast](/assets/images/posts/2019/SDYC-windy-forecast--2019-03-23-24.png) _Click for weather current updates from windy.com_](https://www.windy.com/32.715/-117.225/wind?32.711,-117.225,15,m:ezGacTM)

#### Let's Track Actual Weather to Forecast Models

-    **ECMWF**  (EU) Very accurate model provided by European Centre for Medium-Range Weather Forecasts. Clear winner compared to other forecast models. Since the model is commercial, only few companies in the World offer it.  
-    **GFS** (NOAA) Basic free model provided by National Oceanic and Atmospheric Administration with not so good resolution. Compared to other models GFS can fail in mountain areas, and by forecasting clouds and precipitation. Since the model is free, majority of weather applications use GFS.  
-    **NAM** (NOAA)  Regional mesoscale model run by NCEP. Provides better resolution than global models.  
-    **NEMS** (SWISS/NOAA)  Very accurate model developed by NOAA, but improved and computed by Swiss Meteoblue. Excels in all parameters especially in Alpine areas.  


### Planning

:file_folder: [Regatta Planning Folder](https://drive.google.com/drive/folders/1Qttf_JASqhvfxoMUBV9JqhaxyFOPh3t-)

Please register to help us get a headcount. Then reach out with ideas... maybe we can try to arrange room/group discount at a hotel, and plan some activities.  **All help in organizing, adding additional ideas, changes, etc. in our planning document/folder is encouraged!** Especially trip activity ideas! Let's make the most of it and have fun together!
