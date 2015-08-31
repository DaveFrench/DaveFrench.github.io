---
layout: page
title: Interior Refurbishment
permalink: /interiors/
published: true
---



<div class="posts">
  {% for post in site.posts %}
  	{% if post.categorys contains 'interiors' %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.content }}
      </div>

    </article>
    {% endif %}
  {% endfor %}
</div>
