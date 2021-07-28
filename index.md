---
layout: default
---
# 投稿一覧

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </p>
  {% endfor %}
</ul>
