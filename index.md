---
layout: default
---

## Felt Cute Will Delete Later 

Getting started on doing some more posting. Just wanted to test this out. 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
