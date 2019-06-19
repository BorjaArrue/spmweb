---
layout: blog
title: Blog
---

<div class="container">
	<ul>
	  {% for post in site.posts %}
	    <li>
	      <a href="{{ post.url }}">{{ post.title }}</a>
	      {{ post.excerpt }}
	    </li>
	  {% endfor %}
	</ul>
</div>