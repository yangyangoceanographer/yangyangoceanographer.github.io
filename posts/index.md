---
layout: three_posts
title: Posts
---

<ul id="posts">
{% for post in site.posts %}
<li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y %b %d" }}</li>
{% endfor %}
</ul>
