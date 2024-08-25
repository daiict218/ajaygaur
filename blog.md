---
layout: default
title: "Blog"
permalink: /blog/
---

# Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}

