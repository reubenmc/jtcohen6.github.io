---
layout: default
title: things
order: 4
---

<ul class="project-list">

{% for thing in site.data.things %}

<li><div><a href="{{ thing.href }}">
  <img src="/images/{{ thing.img }}" alt="" />
  <h2 class="project-caption"><span>{{ thing.title }}</span></h2>
</a></div></li>

{% endfor %}

</ul>
