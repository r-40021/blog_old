---
layout: default
title: ようこそ！
---
# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url }}">{{ page.date | date: }} {{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
