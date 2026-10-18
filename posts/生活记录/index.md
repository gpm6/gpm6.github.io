---
layout: default
title: 生活记录
---

# 生活记录

这里是生活记录分类，下面列出该分类下的文章

{% assign cat_posts = site.posts | where_exp:"p","p.path contains 'posts/生活记录/'" %}
{% for post in cat_posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
