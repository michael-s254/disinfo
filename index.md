---
layout: default
title: "Home"
---

# Front page

Hello.

{% for post in site.posts %}   
  [{{ post.title }}]({{ post.url }})
{% endfor %}

Bye.
