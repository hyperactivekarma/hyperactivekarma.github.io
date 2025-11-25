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

For more details about how this example site works checkout [the github project](https://github.com/jsanz/gh-pages-minima-starter).

Have a great day!!

[gh-site]: https://pages.github.com/
[minima]: https://github.com/jekyll/minima/tree/2.5-stable
[jk]: https://jekyllrb.com/
[gh]: https://help.github.com/en/github/working-with-github-pages
[issue]: https://github.com/jsanz/gh-pages-minima-starter/issues/new/choose
[contact]: https://jorgesanz.net/contact/
