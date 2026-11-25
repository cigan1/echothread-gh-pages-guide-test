---
layout: default
title: Home
---
<h1>EchoThread GitHub Pages Guide Test</h1>
<p>Two posts, two separate threads.</p>
<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
