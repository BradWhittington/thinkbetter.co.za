---
title: Think Better
subtitle: A company focused on business and individual growth in a technological world.
layout: layouts/base.njk
---


## This site is a starting point

Think better was started by Brad Whittington with the goal of helping businesses and individuals to grow. 

We work with businesses to:

- Refine and validate technology strategies
- Structure teams and processes for effective focus & delivery
- Act as a thinking partner / outside perspective
- Build cultures of growth, mentorship, and accountability

We work with individuals to:

- Grow into new roles
- Get perspective on leadership and strategy
- Contextualise themselves inside an organisation

## Some of our thoughts

We try to jot down out thinking and ideas on a regular basis

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

