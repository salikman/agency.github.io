---
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="https://shivasena.github.io/ikea-kitchens{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.content }}<hr />
    </li>
  {% endfor %}
</ul>
