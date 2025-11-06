---
layout: page
title: MixmasterFresh's Blog
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
      {{ post.date | date: "%B %d, %Y" }} <span style="margin: 0 10px;">•</span> <a href="{{ post.url }}">{{ post.title }} </a>
  {% endfor %}
</ul>
