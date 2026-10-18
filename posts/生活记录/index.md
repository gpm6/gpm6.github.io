---
layout: default
title: 生活记录
---

# 生活记录

下面列出生活记录分类的文章：

{% assign cat_posts = site.posts | where_exp:"p","p.path contains 'posts/生活记录/'" %}
{% for post in cat_posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
