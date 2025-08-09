---
layout: default
title: 首页
---

欢迎访问我的个人主页。
<ul class="post-list">
  {% for post in site.posts limit:2 %}
    <li class="post-item">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

