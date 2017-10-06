---
layout: projects
title: Projects
order: 1
headline: We’re bringing IBMers together to make and inspire.
---

{% for projects in site.projects %}
<li class="c-project__list-item">
  <a class="c-project__list-anchor" href="{{ projects.url | prepend: site.baseurl }}">
    <div class="c-project__title-container">
      <h2 class="f3 c-project__title">{{ projects.headline }}</h2>
    </div>
    <img class="c-project__image" src="{{ p.url | prepend: site.baseurl }}/images/dd-framed.png" alt="">
  </a>
</li>
{% endfor %}
