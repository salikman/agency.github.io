---
layout: default
---
<<<<<<< HEAD
{%- for post in site.categories.jekyll -%}

         <h2><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2>
         {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
         <span class="post-meta">{{ post.date | date: date_format }}</span>
        {{ post.content }}<hr />

{%- endfor -%}
=======
{% for post in site.categories.jekyll %}

    {{ post.title }}

{% endfor %}
>>>>>>> ef8c812518ed7d7bd525dbaef0e96108dd6f34ca
