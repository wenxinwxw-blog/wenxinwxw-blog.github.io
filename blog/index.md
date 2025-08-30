---
layout: default
title: Blog
---

# Blog
Latest posts:

{% assign posts_list = site.pages | where_exp:'p','p.path contains "_posts"' %}
(Posts appear when you add them to `_posts`)
