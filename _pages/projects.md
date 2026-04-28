---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
<div class="card hoverable p-3" markdown="1">
{{ project.content }}
</div>
{% endfor %}
