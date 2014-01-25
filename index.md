---
layout: page
title: Ignasi Garcia Font
tagline: Lead developer at IPC Media, HTML5 games enthusiast, loves skateboarding.
---
{% include JB/setup %}

<h1>Blog posts</h1>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

