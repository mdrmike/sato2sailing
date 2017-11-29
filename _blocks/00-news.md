---
title: "News"
location: sidebar
---

<header><h3 class="page-heading">{{ blocks.title }}</h3></header>
<ul class="post-list text-muted list-unstyled">
{% for post in site.posts %}
  <li>
    {% assign date_format = site.minima.date_format | default: "%m/%-d/%y" %}
    <h4>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}</a>
        {% if post.last_modified_at > post.date %} <span class="label label-info">updated</span>{% endif %}
      </h4>
  </li>
{% endfor %}
</ul>
