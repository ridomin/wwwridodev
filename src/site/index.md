---
title: Rido.Dev
subtitle: Rido home site
layout: layouts/base.njk
date: 2019-03-11
---


## Open Source Projects

Here are some of my active projects in 2019:

- [MSIX Catalog](https://github.com/ridomin/msix-catalog) WPF tool showing installed APPX/MSIX packages
- [X509Online](https://x509online.azurewebsites.net) [was CertCentral] An experiment to share X509 public keys linked to GitHub accounts
- [RidoUWP](https://github.com/ridomin/ridouwp) UWP sample control to show app packaging information

## Content

Some docs and samples I've contributed to:

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("MMM d, y") }}</time>
  </li>
{%- endfor -%}
</ul>




