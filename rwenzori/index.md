---
layout: post
title: Mount Rwenzori, Uganda
excerpt: "Rwenzori Mountains Uganda - commemorate centennial climb"
search_omit: true
share: true

---

In June 2006 I took part in the 100 year anniversary of the first climb to the summit of Mount Rwenzori (The Mountains of the Moon) straddling the border between Uganda and the Democratic Republic of Congo (DRC). Using time series of satellite images and old maps I studied the change in landcover and glaciers, presented as talks and posters, and a training exercise.

### Movie

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.image %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
