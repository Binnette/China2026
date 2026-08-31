---
layout: default
title: China 2026 Travel Log 🇨🇳
---

<h2>Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>