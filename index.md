---
layout: default
title: ようこそ！
---
# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.baseurl }}">{{ post.date | date: "%y年%m月%d日" }} {{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
