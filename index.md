---
layout: default
title: Projects
order: 1
headline: We bring IBMers together to make.
---

{% for projects in site.projects %}
{: .c-post-list }
- [{{ projects.title }}]({{ projects.url | prepend: site.baseurl }}){: .c-post-list-link }
{% endfor %}
