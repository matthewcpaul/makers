---
layout: projects
title: Projects
order: 1
headline: We bring IBMers together to make.
---

{% for projects in site.projects %}
<li class="c-project__list-item">
  <a href="{{ projects.url | prepend: site.baseurl }}">{{ projects.headline }}</a>
</li>
{% endfor %}
