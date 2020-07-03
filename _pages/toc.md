---
layout: default
title: toc
permalink: /toc/
---

<ul>
    {% for pages in site.pages %}
      {% if pages.category == "doc" %}
        <li><a href="{{ pages.url }}">{{ pages.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

[doc1](/test/doc1/)