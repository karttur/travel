---
layout: post
title: Lake Kyoga surveillance from air and boat.
excerpt: "Lake Kyoga surveillance."
search_omit: true
share: true

---

Photos and movies for surveys and sampling missions in Lake Kyoga, Uganda. The scientific results of the study [integrated management of Lake Kyoga natural resources](https://karttur.github.io/professional/lakekyoga/) are available on my [professional project pages](https://karttur.github.io/professional/projects/).

### Movie

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.image %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
