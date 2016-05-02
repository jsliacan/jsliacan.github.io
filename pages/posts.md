---
layout: page
title: Posts
permalink: /posts/
---

# List of posts
<ul class="post-list">
{% for post in site.posts %}	
	<h3><a href="{{ post.url }}"><small>{{ post.title }}</small></a> <small><strong>[{{ post.date | date: "%B %e, %Y" }}]</strong> </small></h3>
{% endfor %} 
</ul>
