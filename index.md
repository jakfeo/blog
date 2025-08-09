---
layout: jakfeo
title: 首页
---

# 欢迎来到我的博客！

这里是我的个人博客主页，分享技术、生活和更多内容。

<div class="columns-3">
  <div>
    <h3>技术分享</h3>
    <p>探索最新的编程技巧、开源项目和工具。</p>
  </div>
  <div>
    <h3>生活点滴</h3>
    <p>记录生活中的美好瞬间和感悟。</p>
  </div>
  <div>
    <h3>读书笔记</h3>
    <p>分享我阅读过的书籍和学习心得。</p>
  </div>
</div>

---

## 最新文章

<ul>
  {% raw %}{% for post in site.posts limit:5 %}{% endraw %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
  {% raw %}{% endfor %}{% endraw %}
</ul>
