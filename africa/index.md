---
layout: post
title: Travels in Africa
excerpt: "Travels in Africa"
search_omit: true
share: true
---

<ul class="post-list">
  {% for post in site.categories.project %}
    {% if post.continent == 'africa' %}

      {% assign domain = post.projurl %}

      <li><article>

      <a href="..{{ domain }}">{{ post.title }}</a>

      (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">
      {{ post.date | date: "%Y" }}</time></span>).

      {% if post.summary %}
        <span style="font-size: 80%; display: block;">{{ post.summary | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}
        </span>
      {% endif %}
    {% endif %}
    </article></li>
  {% endfor %}
</ul>
