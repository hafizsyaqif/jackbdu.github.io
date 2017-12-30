---
layout: default
title: Projects
permalink: /projects/
---

<h1>{{ page.title }}</h1>

<div class="posts">

  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="date">
        {{ post.date | date: "%Y" }}
      </div>

      <div class="entry">
        <p>{{ post.description }}</p>
      </div>

      <a href="{{ site.baseurl }}{{ post. url}}"><img src="{{ site.baseurl }}/images{{ post. url}}preview.jpg"/></a>

    </article>
  {% endfor %}

</div>
