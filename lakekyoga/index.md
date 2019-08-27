---
layout: post
title: Lake Kyoga surveillance from air and boat.
excerpt: "Lake Kyoga surveillance."
search_omit: true
share: true

---

Lake Kyoga surveys and samplings.

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
