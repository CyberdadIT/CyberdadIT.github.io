---
layout: page
title: Blog
permalink: /blog/
---

# Blog Posts

All my articles and writeups will appear here.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>