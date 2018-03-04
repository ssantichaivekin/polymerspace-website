---
layout: splash
title: Projects
permalink: /projects/
classes: 
  - wide
---

<!-- This is the projects landing page. -->

## Ongoing projects

You can come up with your own project and tell the board. We will provide the space and the materials for you.

<div class="grid__wrapper">
{% for post in site.projects %}
    {% include archive-single.html type="grid" %}
{% endfor %}
</div>

<!-- Add archived projects here? -->