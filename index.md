---
layout: default
title: やまだ Blog
---
# About
こんにちは、「やまだ」です。
普段はWebアプリの開発を行っています。

詳しくは<a href="https://r-40021.github.io/blog/2021/07/28/introduce.html">こちら</a>をご覧ください。

# 記事一覧

<div>
  {% for post in site.posts %}
    <p>
      {{ post.date | date: "%Y/%m/%d" }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </p>
  {% endfor %}
</div>
