---
layout: default
title: Home
group: "navPrimary"
navTitle: "Home"
---

# {{ page.title }}

Welcome to Exmoor Logs based in Lynton, Devon.

We have high quality seasoned logs available for year round delivery throughout the North Devon area.

All logs produced by Exmoor Logs have been sourced from local and well managed woodlands.

<ul class="posts">
	{% for post in site.posts %}
		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
