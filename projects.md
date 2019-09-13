---
permalink: /projects/index.html
---

<p>Are you using Parity for a project?  We'll be happy to include your project here.  Feel free to open an issue or send a pull request <a href="https://github.com/licensezero/paritylicense.com/issues">via GitHub</a>.</p>

<ul class="projects">
{% for project in site.projects reversed %}
<li>
    <a href="{{project.url}}">{{project.title}}</a>{% if project.description %}, {{project.description}}{% endif %}{% if project.language %}, in {{project.language}}{% endif %}
  </li>
  {% endfor %}
</ul>

