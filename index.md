---
layout: home
title: 首页
---

# 欢迎来到我们的实验室

我们是一个致力于[研究方向]的研究团队。我们的研究重点包括：

- 研究方向1
- 研究方向2
- 研究方向3

## 最新动态

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 联系我们

- 地址：[实验室地址]
- 邮箱：[联系邮箱]
- 电话：[联系电话] 