---
layout: projects
title: Projects
order: 1
headline: We bring IBMers together to make.
---

{% for projects in site.projects %}
<li class="c-project__list-item">
  <a class="c-project__list-anchor" href="{{ projects.url | prepend: site.baseurl }}">
    <img class="c-project__image" src="/images/dd-framed.png" alt="">
    <div class="c-project__title-container">
      <h4 class="c-project__title">{{ projects.headline }}</h4>
    </div>
  </a>
</li>
{% endfor %}
