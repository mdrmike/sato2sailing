---
title: "Upcoming Regattas"
location: sidebar
published: true

# github emoji list https://gist.github.com/rxaviers/7360908
links:
- text: Gaucho Regatta Info
  emoji: cow
  url: /news/regatta/pcisa/gaucho/
  #target: _blank

- text: Notice of Race (NOR)
  emoji: information_source
  url: https://hssailing.org/schedule_news/docs/pcisa_docs/2018-GOLDEN-BEAR-NOR.pdf
  target: _blank
  
- text: UCSB Gaucho Planning
  published: true
  emoji: small_orange_diamond
  url: https://drive.google.com/drive/folders/1HwRK0Rt1rOftq093EAiLmv_Ld_Fpj71V?usp=sharing
  target: _blank

- text: #spacer 
  published: true
  emoji: 
  url: 

- text: SoCal5 (last regatta?)
  emoji: five
  url: #/news/regatta/
  #target: _blank

- text: Notice of Race (NOR)
  emoji: information_source
  url: https://hssailing.org/schedule_news/docs/pcisa_docs/2017-2018-PCISA-SoCal-NOR_1.pdf
  target: _blank
  
- text: SDYC Planning Folder
  published: true
  emoji: small_orange_diamond
  url: https://drive.google.com/open?id=1pTIjay3FI0YzDlB8KH_IPlLoHzvGCEDb
  target: _blank

- text: #spacer
  published: false
  emoji: 
  url: 
  #target: _blank
    
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
