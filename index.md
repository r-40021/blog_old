---
layout: default
title: やまだ Blog
---
# About
こんにちは、「やまだ」です。
普段はWebアプリの開発を行っています。

詳しくは<a href="{{ site.baseurl }}{{ site.posts[0].url }}">こちら</a>をご覧ください。

# 記事一覧

<div>
  {% for post in site.posts %}
    <p>
      {{ post.date | date: "%Y/%m/%d" }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </p>
  {% endfor %}
</div>
