---
layout: page
title: Foo
permalink: /foo/
---

{% for album in site.data.albums %}
  {{ album.title }}
  {{ album.artist }}
{% endfor %}
This is a list

* one
* two
* three

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}    
