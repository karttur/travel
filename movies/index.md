---
layout: resume
title: Movies
excerpt: "Archive of movies and animations"
search_omit: true
share: true

---
### Movies

<ul class="post-list">
  {% for post in site.categories.movie %}
    {% include publication.html post=post %}
  {% endfor %}
</ul>

### Presentation animations/movies

<ul class="post-list">
  {% for post in site.categories.talk %}
    {% if post.doctype == "movie" %}
      {% include publication.html post=post %}
    {% endif %}
  {% endfor %}
</ul>

### Supplement animations/movies

<ul class="post-list">
  {% for post in site.categories.supplement %}
    {% if post.doctype == "movie" %}
      {% include publication.html post=post %}
    {% endif %}
  {% endfor %}
</ul>
