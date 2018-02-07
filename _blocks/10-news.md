---
title: "News"
location: sidebar
# post_in_seconds
#   = jekyll post time (unix format = seconds since 1970)
# recent_posts_length
#   = timeframe in seconds to determine if post should be flagged as updated
#
#     86400 seconds per day 
#     2419200 = 4wks
#     2678400 = 31 days  
#     3628800 = 6wks
---

{% assign date_format = site.minima.date_format | default: "%m/%d" %}

<header><h3 class="page-heading">{{ blocks.title }}</h3></header>
<ul class="post-list text-muted list-unstyled">

{% for post in site.posts limit:5 %}
  {% assign post_in_seconds = post.last_modified_at | date: "%s" | plus: 0 %}
  {% assign recent_posts_length = "now" | date: "%s" | minus: 2419200 %}
  {% assign post_updated = post.last_modified_at | date: date_format %}
  {% capture post_date %}<small><span class="">{{ post.date | date: date_format }}</span></small>{% endcapture %}

{% comment %} TEST: if post has been updated AND post is recent to label {% endcomment %}
  {% if post_in_seconds > recent_posts_length %}
  {% capture label_new %}<span class="label label-primary">new</span>{% endcapture %}
    {% if post.last_modified_at > post.date %}
      {% assign label_new = '' %}
      {% capture label_updated %}<span class="label label-info">Updated <span class="badge">{{ post_updated }}</span></span>{% endcapture %}
      {% capture label_debug %}
        <span class="label label-success">ORIG {{ post_date }}</span>
        <span class="label label-warning">updated {{ post_updated }}</span>
      {% endcapture %}
    {% endif %}
  {% endif %}

<li>
    <h4>{{ post_date }}
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}</a> {{ label_new }}{{ label_updated }}
      </h4>
</li>
  {% assign post_date = '' %}
  {% assign label_updated = '' %}
  {% assign label_debug = '' %}
{% endfor %}
</ul>
