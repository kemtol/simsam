---
layout: page-portfolio
title: Videoworks
permalink: /videoworks/
tags:
- commercial
- series
- video content
- corporate
- documentary
- music
---

<ul class="page-tags">
  {% for tags in page.tags %}
    <li>{{ tags }}</li>
  {% endfor %}
</ul>

<div class="posts">
  {% for post in site.categories.videoworks %}
    <article class="post">
      <a href="{{ site.baseurl }}{{ post.url }}">
        <img src="http://i.ytimg.com/vi/{{ post.videoid }}/maxresdefault.jpg" />
        {{ post.title }}
      </a>
    </article>
  {% endfor %}
</div>
