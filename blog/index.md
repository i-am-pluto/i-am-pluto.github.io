---
layout: default
title: Writing
---
<h1>Writing</h1>
<ul class="posts">
{% for p in site.posts %}<li><span>{{ p.date | date: "%b %-d, %Y" }}</span><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}</ul>
