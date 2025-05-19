---
layout: base
title: My Eleventy Project 1
---

## My posts

{%- for post in collections.general %}
* [{{ post.data.title }}]({{ post.url }})
{%- endfor %}