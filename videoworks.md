---
layout: page
title: Videoworks
permalink: /videoworks/
---

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
