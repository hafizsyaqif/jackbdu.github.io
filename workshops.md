---
layout: default
title: Workshops
permalink: /workshops/
---

<h1>{{ page.title }}</h1>

<div class="posts">

  {% for post in site.categories["workshops"] %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {% for tag in post.tags %}
        <a style="margin-left: 1em;font-size: 0.7em;" href="{{ site.baseurl }}{{ tag }}">#{{tag}}</a>
      {% endfor %}
      </h1>

      <div class="date">
        {{ post.date | date: "%Y" }}
      </div>

      <div class="entry">
        <p>{{ post.description }}</p>
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}"><img src="{{ site.baseurl }}/media{{ post.url }}preview.jpg"/></a>

    </article>
  {% endfor %}

</div>
