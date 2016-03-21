---
layout: page
title: Foo
permalink: /foo/
---

This is a list

* one
* two
* three

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}    
