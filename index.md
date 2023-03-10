---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Akshay's blog
description : "Thoughts and reflections on product management, productivity, goals and happy life"
---
{% for post in site.posts %}
  <div id="post-short">
    <a class="link-in-post" href="{{site.url}}{{site.baseurl}}{{post.url}}">
      <h3>{{post.title}}</h3>
    </a>
    <i>posted on {{ post.date | date: "%-d %b %Y" }}</i>
  </div>
{% endfor %}
