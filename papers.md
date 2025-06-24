---
title: Papers
nav: true
---

# Accepted Papers

<ol>
{% for paper in site.data.papers %}
  <li>
    <a href="{{ paper.url || relative_url }}">
      {{ paper.title }}
    </a> - {{ paper.authors }}
  </li>
{% endfor %}
</ol>
