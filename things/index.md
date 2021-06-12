---
layout: default
title: things
order: 4
lang: en
ref_en: things
things:
- title: theatrical
  href: the-theatre
  img: merchant.JPG

- title: statistical
  href: stat-final-projects
  img: table.png
  
- title: rhetorical
  href: /posts
  img: blurry.png
  
- title: classical
  href: greco-roman-authors
  img: greco-roman.png

---

<ul class="project-list">

{% for thing in page.things %}

<li><div><a href="{{ thing.href }}">
  <img src="/images/{{ thing.img }}" alt="" />
  <h2 class="project-caption"><span>{{ thing.title }}</span></h2>
</a></div></li>

{% endfor %}

</ul>
