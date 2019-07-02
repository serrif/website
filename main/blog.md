---
title: Server blog
permalink: /blog/

layout: home

hero:
  image: ../assets/img/hero/WVy0BOAMU9.png
  callout:
    text: Server blog

tagline: We're a modern, creative community.
---

## Latest posts
<ul>
				{% for post in site.posts %}
					<li>
						{{ post.content }}
						<span>{{ post.date | date: "%B %e, %Y" }}</span>
					</li>
				{% endfor %}
</ul>
