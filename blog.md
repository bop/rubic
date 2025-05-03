---
layout: default
title: Blog
---
<h2 class="shadow text-center">Jalons</h2>
<br />
<div class="main">
<div class="modal modal-content">
<ul class="nope col-10 row">
	<br />
  {% for post in site.posts %}
    <li>
<br />
<h3 class="small"><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
<hr class="position-relative py-2 px-4 start-50 translate-middle" />
  {% endfor %}
</ul>
<br />
<br />
</div>
</div>
<br />
