---
layout: page
title: Videoworks
permalink: /videoworks/
---

<div class="posts">
  {% for post in site.categories.videoworks %}
    <article class="post">
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/{{ post.videolink }}" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </article>
  {% endfor %}
</div>
