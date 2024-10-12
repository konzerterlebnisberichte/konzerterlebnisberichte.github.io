---
layout: page
title: Archiv
permalink: /archiv/
---

Im folgenden eine komplette Liste aller Posts, für die Vollblut-Hobbyhistoriker unter euch:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d"}} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>