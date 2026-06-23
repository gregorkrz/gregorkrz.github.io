---
layout: page
title: Projects
permalink: /projects/
description: A selection of my research projects.
nav: true
nav_order: 3
---

<!-- _pages/projects.md -->
<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
<h2>{{ project.title }}</h2>
<p class="text-muted">{{ project.description }}</p>

{{ project.content }}

{% unless forloop.last %}
<hr>
{% endunless %}
{% endfor %}
</div>
