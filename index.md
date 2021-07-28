---
layout: default
title: ようこそ！
---
# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ site.baseurl }}{{ post.baseurl }}">{{ post.date | date: "%Y年%m月%d日" }} {{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
