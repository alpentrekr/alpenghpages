---
title: Home
---

# Welcome

This is my starter GitHub Pages site built with Jekyll.

## What this site is for

- Documentation
- Notes
- Blog posts
- Project updates

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
