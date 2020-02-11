---
layout: default
title: Staff
---
<h1>Elecciones en Sudamérica 2020</h1>
<ul>
  {% for pais in site.paises %}
    <li>
      <h2><a href="{{ pais.url }}">{{ pais.name }}</a></h2>
    </li>
  {% endfor %}
</ul>
