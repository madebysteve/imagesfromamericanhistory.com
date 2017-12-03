---
title: Images from American History
---

{% for post in site.posts %}
  <article>
    <header>
      <h1 class="post-title">
        <a href="{{ post.url }}">{{ post.title }}</a>
      </h1>
      <h2 class="post-date">{{ post.date | date: '%B %d, %Y' }}</h2>
    </header>
    {{ post.content }}
  </article>
{% endfor %}
