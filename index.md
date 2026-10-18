---
layout: default
title: 首页
---

# 欢迎来到 H 的生活记录站

- [生活记录](posts/生活记录/)
- [股市随笔](posts/股市随笔/)
- [人文风景](posts/人文风景/)
- [人像](posts/人像/)
- [资料库](library/)

---

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

