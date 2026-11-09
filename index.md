---
layout: default
---
<section class="card hero">
<div>
<span class="eyebrow">dwarf planet · self-hosted</span>
<h1>Still a planet.</h1>
<p>I'm Parikshit. I build systems from the ground up and run my own software: a family of apps, and an agent that keeps improving them. Notes from a small world.</p>
<div class="btns"><a class="btn" href="/blog/">read the writing</a><a class="btn ghost" href="#projects">see what I'm building</a></div>
</div>
<div class="orbit" aria-hidden="true"><div class="ring"></div><div class="p"></div></div>
</section>

<div class="stats"><span><b>9</b>apps</span><span><b>1</b>postgres</span><span><b>1</b>agent on call</span><span><b>0</b>clouds I rent</span></div>

<h2 id="projects">What I'm building</h2>
<div class="grid">
<div class="card"><span class="eyebrow">from scratch</span><b class="card-t">A container runtime</b><p>Namespaces, cgroups, seccomp and pivot_root, written to learn what Docker really does.</p></div>
<div class="card"><span class="eyebrow">the family</span><b class="card-t">Nine self-hosted apps</b><p>Hub, Hinger, OpenFit, Compound, Notes and more, sharing one brand kit and one Postgres server.</p></div>
<div class="card"><span class="eyebrow">agent</span><b class="card-t">Chotu</b><p>Changes the apps on its own. Tests, reviews, ships and records every change, and rolls back through git tags when it breaks something.</p></div>
<div class="card"><span class="eyebrow">observability</span><b class="card-t">Pulse</b><p>Usage beacons and an outcomes endpoint on every app, so I can see what actually works.</p></div>
</div>

<h2>Latest writing</h2>
<ul class="list">
{% for p in site.posts limit:5 %}<li><time>{{ p.date | date: "%Y-%m-%d" }}</time><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}</ul>
