---
layout: default
title: 首页
---

# 👋 欢迎来到 Jamie 的极客小屋

> 一点代码，一点思考，一点生活。

这里是我的个人博客，用于记录学习笔记、编程技巧和有趣的想法。

## 📚 最新文章
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}

更多文章 → [归档](/archives)
