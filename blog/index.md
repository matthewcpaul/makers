---
layout: blog
title: Blog
order: 2
headline: Blog
---

{% for posts in site.posts %}
{: .c-post-list }
- [{{ posts.title }}]({{ posts.url | prepend: site.baseurl }}){: .c-post-list-link }
{% endfor %}
