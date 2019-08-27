---
layout: page
title: "Travels"
excerpt: "Travels"
search_omit: true
share: true
---

## Africa

<ul class="post-list">
  {% for post in site.categories.project %}
    {% if post.continent == 'africa' %}
      {% if post.projurl contains 'http' %}
        {% assign domain = '' %}
      {% else %}
        {% assign domain = post.projurl %}
      {% endif %}
      <li><article>

      <a href="{{ domain }}{{ link.url }}">{{ post.title }}</a>

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
