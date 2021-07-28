---
layout: default
title: やまだ Blog
---
# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ site.baseurl }}/{{ post.url }}">{{ post.date | date: "%Y年%m月%d日" }} {{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
