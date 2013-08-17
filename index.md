---
layout: page
title: سمیکالن؛
tagline: در جستجوی سمیکالن از دست رفته 
---
{% include JB/setup %}

<ul class="posts unstyled">
  {% for post in site.posts %}
    <li><h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }} ...
    <hr>
    </li>
  {% endfor %}
</ul>
