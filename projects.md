---
layout: splash
title: Projects
permalink: /projects/
classes: 
  - wide
feature_row:
  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

<!-- This is the projects landing page. -->

## Ongoing projects

You can come up with your own project and tell the board. We will provide the space and the materials for you. You can submit your project proposal through this google form.

<div class="grid__wrapper">
{% for post in site.projects %}
    {% include archive-single.html type="grid" %}
{% endfor %}
</div>

{% include feature_row %}

<!-- Add archived projects here? -->