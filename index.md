---
layout: default
title: やまだ Blog
---
# About
こんにちは、「やまだ」です。
普段はWebアプリの開発を行っています。

詳しくは<a href="{{ site.baseurl }}/{{ site.posts[0].url }}">こちら</a>をご覧ください。

# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date: "%Y年%m月%d日" }} {{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
