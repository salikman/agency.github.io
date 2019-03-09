---
layout: default
---
{%- for post in site.categories.ikea-kitchens -%}
    <h2><a href="{{ post.url }}">{{ post.title | escape }}</a></h2>
    {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
    <span class="post-meta">{{ post.date | date: date_format }}</span>
    {{ post.content }}<hr />
{%- endfor -%}

