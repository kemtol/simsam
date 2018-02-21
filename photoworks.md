---
layout: page-portfolio
title: Photoworks
permalink: /photoworks/
page-cat: photoworks
tags:
- commercial
- series
- video content
- corporate
- documentary
- music
---

<div class="posts">
  {% for post in site.categories.photoworks %}
    <article class="post {% for tags in post.tags %}{{ tags }} {% endfor %}">
      <a href="{{ site.baseurl }}{{ post.url }}">
        <img src="post.featimgurl" />
        <span>{{ post.title }}</span>
      </a>
    </article>
  {% endfor %}
</div>
