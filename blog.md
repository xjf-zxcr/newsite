---
layout: page
title: Blog
permalink: /blog/
---

![4 picture](/assets/4.png)
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
			{{ post.excerpt }}
		</li>
	{% endfor %}
</ul>
