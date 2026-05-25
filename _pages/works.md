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

# 网格布局 + 缩略图设置
entries_layout: grid
show_excerpts: false          # 不显示文字摘要，只显示缩略图和标题
sort_by: date
sort_order: reverse           # 按时间倒序，最新作品在最前


# 缩略图显示设置（主题原生支持）
classes: wide                  # 让网格更宽，多放几列
header:
  image: false
---
