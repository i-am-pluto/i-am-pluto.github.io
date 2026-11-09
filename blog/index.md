---
layout: default
title: Writing
---
<span class="eyebrow">archive</span>
<h1>Writing</h1>
<ul class="list">
{% for p in site.posts %}<li><time>{{ p.date | date: "%Y-%m-%d" }}</time><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}</ul>
