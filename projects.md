---
layout: archive
title: Projects
permalink: /projects/
---

<!-- This is the projects landing page. -->

{% for post in site.projects %}
    {% include archive-single.html %}
{% endfor %}