---
layout: post
title: Mount Elgon, Uganda
excerpt: "Mount Elgon hike"
search_omit: true
share: true

---

Hike to the top of Mount Elgon.

### Movie

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "mtelgon" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.image %}
  {% if post.projectid == "mtelgon" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
