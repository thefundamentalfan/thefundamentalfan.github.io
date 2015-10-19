---
layout: default
title: All Posts
---

## Here's a list of all the old posts.

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
