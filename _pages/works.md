---
title: Art Works
permalink: /works/
layout: single
author_profile: true
---

{% for post in site.categories.art %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
