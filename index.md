---
layout: default
---
<h1>Hi, I'm Parikshit.</h1>
<p class="lede">I build systems from the ground up and run my own software. These days that means a family of self-hosted apps, and an agent that keeps improving them.</p>

<h2 id="projects">What I'm building</h2>
<div class="cards">
<div class="card"><b>A container runtime from scratch</b>Namespaces, cgroups, seccomp and pivot_root, written to understand what Docker really does.</div>
<div class="card"><b>A self-hosted app family</b>Hub, Hinger, OpenFit, Compound, Notes, Pulse and more. They share one brand kit and one Postgres server.</div>
<div class="card"><b>Chotu</b>An agent that changes the apps on its own. It tests, reviews, ships, and records every change, with git-tag rollback if something breaks.</div>
<div class="card"><b>Pulse</b>Observability for it all: usage beacons and outcome endpoints on every app.</div>
</div>

<h2>Latest writing</h2>
<ul class="posts">
{% for p in site.posts limit:5 %}<li><span>{{ p.date | date: "%b %-d, %Y" }}</span><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}</ul>
<p><a href="/blog/">All posts →</a></p>
