---
title: Diffs of the Parity Public License
permalink: /diffs/index.html
layout: default
---

<ul>
  {% for diff in site.diffs reversed %}
    <li>
      <a href="{{diff.url}}">{{diff.from}} v. {{diff.to}}</a>
    </li>
  {% endfor %}
</ul>
