---
layout: page_main
title: About us
permalink: /about/
---

### About us

Healthy Mind Tech is a start-up organization with the vision of improving people’s lives using technology.

### Our team

Our team has extensive experience in the areas of software and hardware and a track record of
successfully delivering products and services in these areas. In particular, we have expertise in
software development, project management, finance, leadership, marketing, healthcare, digital
health technology, robotics, and automation.

### Contact

<ul class="contact-list">
    <li class="p-name">
    {%- if site.author -%}
        {{ site.author | escape }}
    {%- else -%}
        {{ site.title | escape }}
    {%- endif -%}
    </li>
    {%- if site.cvr_number -%}
    <li>CVR: {{ site.cvr_number }}</li>
    {%- endif -%}
    {%- if site.address -%}
    <li>Address: {{ site.address }}</li>
    {%- endif -%}
    {%- if site.email -%}
    <br/>
    <li><a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a></li>
    {%- endif -%}
</ul>