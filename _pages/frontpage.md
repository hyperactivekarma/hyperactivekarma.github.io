---
permalink: /
layout: default
title:
list_title:
---

<img src="./assets/imgs/allegedlyme.png" width="400px">

## {{ page.list_title }}

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
    - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>
