---
title: "Regatta Links"
location: sidebar
published: false

# github emoji list https://gist.github.com/rxaviers/7360908
links:
- text: Golden Bear NOR
  emoji: information_source
  url: https://hssailing.org/schedule_news/docs/pcisa_docs/2018-GOLDEN-BEAR-NOR.pdf
  target: _blank
    
- text: 2018 Spring Scores
  emoji: large_blue_circle
  url: https://scores.hssailing.org/s18/
  target: _blank

- text: All HSS Scores
  emoji: large_orange_diamond
  url: https://scores.hssailing.org/seasons/
  target: _blank
  
- text: booya
  published: false
  emoji: information_desk_person
  url: 
  target: _blank
      
- text: foo
  published: false
  emoji: triangular_flag_on_post
  url: 
  target: _blank
  
---

<header><h3 class="page-heading">{{ blocks.title }}</h3></header>
<ul class="post-list text-muted list-unstyled">
{% for link in page.links %}
  {% if link.published != false %}
  <li>
    <h4>:{{ link.emoji }}: <a href="{{ link.url }}" rel="nofollow" target="{{ link.target }}">{{ link.text }}</a></h4>
  </li>
  {% endif %}
{% endfor %}
</ul>
