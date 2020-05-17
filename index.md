---
layout: default
title: "Home"
---

# Front page

Hello.

{% for post in site.posts %}   
  [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

Bye.
