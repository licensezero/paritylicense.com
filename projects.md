<ul class="projects">
  {% for project in site.projects reversed %}
  <li>
    <a href="{{project.url}}">{{project.title}}</a>{% if project.description %}, {{project.description}}{% endif %}{% if project.language %}, in {{project.language}}{% endif %}
  </li>
  {% endfor %}
</ul>

