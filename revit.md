---
layout: page
title: Revit
permalink: /revit/
published: true
---


<div class="posts">
  {% for post in site.posts %}
    {% if post.categorys contains 'revit' %}
    <article class="post">
 
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
 
      <div class="entry">
        {{ post.excerpt }}
      </div>

    </article>
    {% endif %}
  {% endfor %}
</div>
