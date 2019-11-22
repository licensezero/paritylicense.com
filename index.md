---
title: The Parity Public License
description: the free for open software license
layout: default
---

[Parity](versions/7.0.0.html) is a public `LICENSE` for software that requires users who build with your software to share their work with the community, too.  In other words, Parity makes your work free for open source, like [GitHub](https://github.com), [Travis CI](https://travis-ci.com), and other services.

<h2 id=projects>Projects</h2>

<ul class="projects">
{% for project in site.projects reversed %}
<li>
    <a href="{{project.url}}">{{project.title}}</a>{% if project.description %}, {{project.description}}{% endif %}{% if project.language %}, in {{project.language}}{% endif %}
  </li>
  {% endfor %}
</ul>

<p>To list your project, send a pull request <a href="https://github.com/licensezero/paritylicense.com">via GitHub</a>.</p>

<h2 id=development>Development</h2>

License development continues in [the GitHub repository](https://github.com/licensezero/parity-public-license).  Feel free to open issues and send pull requests.
