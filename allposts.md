---
layout: default
title: All Posts
---

<h2 style='text-align:center;'> Here's a list of all the old posts. </h2>
<h3 style='text-align:center;'> You can Control-F [Command-F on Mac] by date or keywords in the title. If you can't find a post, don't hesitate to contact us at thefundamentalfan@gmail.com. </h3>

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
