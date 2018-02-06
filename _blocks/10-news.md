---
title: "News"
location: sidebar
# 86400 seconds per day 
# 3628800 seconds = 6wks.
# 2678400 = 31 days.  
# 2419200 = 4wks
---

{% assign current_time = "now" | date: "%s" | plus: 0 %}

<header><h3 class="page-heading">{{ blocks.title }}</h3></header>
<ul class="post-list text-muted list-unstyled">
{% for post in site.posts limit:5 %}
  <li>
    {% assign postseconds = post.last_modified_at | date: "%s" | plus: 0 %}
    {% assign recentpost = current_time | date: "%s" | minus: 2678400 %}
    <h4>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}</a>
        {% if postseconds > recentpost %} <span class="label label-info"> updated</span>{% endif %}
      </h4>
  </li>
{% endfor %}
</ul>
