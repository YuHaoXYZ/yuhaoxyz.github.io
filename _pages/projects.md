---
title: Commercial Projects
permalink: /projects/
layout: single
author_profile: true
---

{% for post in site.categories.commercial %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
