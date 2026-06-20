---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Akshay's blog
description : "Thoughts and reflections on product management, productivity, goals and happy life"
---
{% for post in site.posts %}
  <div class="post-short">
    <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
    <a class="post-title" href="{{site.url}}{{site.baseurl}}{{post.url}}">{{ post.title }}</a>
  </div>
{% endfor %}
