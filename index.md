---
layout: default
title: 首页
---

欢迎访问我的个人主页。
<p>文章数量：{{ site.posts | size }}</p>

<p>全部页面数：{{ site.pages | size }}</p>
<ul>
  {% for page in site.pages %}
    <li>{{ page.url }}</li>
  {% endfor %}
</ul>
