---
layout: default
title: Projects
permalink: /projects/
---

<h1>{{ page.title }}</h1>

<div class="posts">

  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {% for category in post.categories %}
        <a style="padding-left: 1em;font-size: 0.7em;" href="{{ site.baseurl }}{{ category }}">#{{category}}</a>
      {% endfor %}
      </h1>

      <div class="date">
        {{ post.date | date: "%Y" }}
      </div>

      <div class="entry">
        <p>{{ post.description }}</p>
      </div>

      <a href="{{ site.baseurl }}{{ post. url}}"><img src="{{ site.baseurl }}/media{{ post. url}}preview.jpg"/></a>

    </article>
  {% endfor %}

</div>
