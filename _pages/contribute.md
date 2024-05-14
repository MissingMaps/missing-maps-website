---
title: Get Involved
links:
  - link: /contribute/mapswipe/
  - link: /contribute/tasking-manager/
  - link: /contribute/validation/
  - link: /contribute/field-mapping/
  - link: /contribute/advanced-mapping/
  - link: /contribute/mapping-guides/



---

There are lots of way to contribute map data for humanitarian purposes - explore below and have fun!

{::nomarkdown}
{% assign subitems="" | split: ',' -%}
{% for link in page.links %}
  {% assign item=site.pages | find: "url", link.link %}
  {%- if item -%}
    {%- assign subitems=subitems | push: item -%}
  {%- endif %}
{% endfor %}
{% include item_list.html items=subitems %}
{:/nomarkdown}