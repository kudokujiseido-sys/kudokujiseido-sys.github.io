---
layout: page
title: 現在の状況（更新）
permalink: /updates/
---

週1程度の更新を想定しています。

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }}：[{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

