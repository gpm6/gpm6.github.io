---
layout: default
title: 首页
---

# 欢迎来到 H 的生活记录站

这里记录：

- 生活记录（本地走走、外地随行、半游半拍）
- 股市随随笔（看盘日记、走势观察）
- 人文风景（花、城市风景、街景、人文场景）
- 人像（生活化人像）
- 资料库（PDF、书刊、扫描件）

---

## 最新文章

{% for post in site.posts limit:10 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
