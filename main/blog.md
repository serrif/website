---
title: Server blog
permalink: /blog/

layout: home

hero:
  image: ../assets/img/hero/WVy0BOAMU9.png
  callout:
    text: Information center

tagline: We're a modern, creative community.
---

## Latest posts
{% for post in site.posts %}
  <hr style="margin-top: 4.5rem;">
  {% include post.html post=post excerpt=true %}
  <hr style="margin-top: 4.5rem;">
{% endfor %}
