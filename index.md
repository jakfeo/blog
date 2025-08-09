---
layout: default
title: 首页
---

欢迎访问我的个人主页。
<p>文章数量：{{ site.posts | size }}</p>

<p>全部页面数：{{ site.pages | size }}</p>
<p>URL: '{{ post.url }}'</p>
<ul>
  {% raw %}{% for post in site.posts limit:5 %}{% endraw %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
  {% raw %}{% endfor %}{% endraw %}
</ul>

