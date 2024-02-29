---
title: People of Felloe.io
description: "Felloe.io &ndash; All-things Platform Infrastructure"
layout: page
---

## People
<ul>
  {% for author in site.people %}
    <li><a href="{{ author.id }}.html">{{ author.title }}</a></li>
  {% endfor %}
</ul>
