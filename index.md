---
layout: default
title: 首页
---

欢迎访问我的个人主页。
<p>文章数量：{{ site.posts | size }}</p>

<ul>
  {% for post in site.posts limit:2 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a><br>
      <small>{{ post.excerpt }}</small>
    </li>
  {% endfor %}
</ul>
