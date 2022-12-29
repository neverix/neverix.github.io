---
layout: default
title: Home page
permalink: /
---

# [Resume](/pdf/resume.pdf)

# Latest posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
