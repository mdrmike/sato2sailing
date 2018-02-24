---
title: "Treasure Island Regatta"
location: sidebar
published: true

# github emoji list https://gist.github.com/rxaviers/7360908
links:
- text: Map
  emoji: earth_americas
  url: https://www.google.com/maps/place/Treasure+Island+Sailing+Center/@37.8191229,-122.3669557,17z/data=!3m1!4b1!4m5!3m4!1s0x8085802e2f01cd4f:0x8cd7b3960e477b13!8m2!3d37.8191187!4d-122.364767
  target: _blank

- text: Parking
  emoji: car
  url: https://drive.google.com/open?id=19gho1hcHYA-wQJS8FGrJI2nzwQlFU4Kv
  target: _blank

- text: Golden Bear Info
  emoji: bear
  url: /news/regatta/pcisa/golden-bear/
  #target: _blank

- text: 
  emoji: 
  url: 
  
- text: Silver Scores
  emoji: checkered_flag
  url: https://scores.hssailing.org/s18/pcisa-golden-bear-silver/
  target: _blank

- text: Silver Full Scores
  #published: false
  emoji: ledger
  url: https://scores.hssailing.org/s18/pcisa-golden-bear-silver/full-scores/
  target: _blank

- text: Rotations (Sail Numbers)
  emoji: recycle
  url: https://scores.hssailing.org/s18/pcisa-golden-bear-silver/rotations/
  target: _blank

- text: Sailors Instructions (course)
  emoji: memo
  url: https://scores.hssailing.org/s18/pcisa-golden-bear-silver/notices/sailing-instructions.pdf
  target: _blank

- text: 
  emoji: 
  url: 
  #target: _blank
    
- text: Notice of Race (NOR)
  emoji: information_source
  url: https://hssailing.org/schedule_news/docs/pcisa_docs/2018-GOLDEN-BEAR-NOR.pdf
  target: _blank
    
- text: PCISA ALL Scoring
  emoji: triangular_flag_on_post
  url: https://scores.hssailing.org/s18/
  target: _blank

- text: All HSS Scores
  published: false 
  emoji: large_orange_diamond
  url: https://scores.hssailing.org/seasons/
  target: _blank
  
---

<header><h3 class="page-heading">{{ blocks.title }}</h3></header>
<ul class="post-list text-muted list-unstyled">
{% for link in page.links %}
  {% if link.published != false %}
  <li>
    <h4>{% if link.emoji %}:{{ link.emoji }}:{% else %}&nbsp;{% endif %} <a href="{{ link.url }}" rel="nofollow" target="{{ link.target }}">{{ link.text }}</a></h4>
  </li>
  {% endif %}
{% endfor %}
</ul>
