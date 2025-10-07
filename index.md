---
layout: default
title: 首页
---

# 欢迎来到我的博客 👋

我是洪紫涵，一名心理学学习者，这里记录我的学习笔记和思考。

## 📚 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y年%m月%d日" }}
{% endfor %}

## 📫 联系我 

- GitHub: [zihanhong6](https://github.com/zihanhong6)
- Email: 3245222469@qq.com
