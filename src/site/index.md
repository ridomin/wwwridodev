---
title: Rido.Dev
subtitle: Rido home site
layout: layouts/base.njk
---


## Open Source Projects

Here are some of my active projects:

- [MSIX Catalog](https://github.com/ridomin/msix-catalog) 
- [Cert Central](https://bit.ly/certcentral)
- [RidoUWP](https://github.com/ridomin/msix-catalog) demo UWP library


## Content

Articles, docs and other contents

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>




