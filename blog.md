---
layout: default
title: Blog
---
<h2 class="shadow text-center">Latest Posts</h2>
<br />
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="/rubic{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
<br />
<hr class="position-relative py-2 px-4 start-50 translate-middle" />
<br />
