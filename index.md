---
layout: default
title: Homepage
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>

[Welcome](/posts/welcome.md)
[My Blog](https://windfiresteel.github.io/wfs-blog)
[About](http://windfiresteel.github.io/about)
[Posts](/posts)
[Practice](practice.md)
