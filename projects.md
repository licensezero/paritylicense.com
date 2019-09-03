<ul class="projects">
{% for project in site.projects %}
<li><a href="{{project.url}}">{{project.title}}</a></li>
{% endfor %}
</ul>

