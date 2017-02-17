---
layout: page
title: Projects
permalink: /projects/
navigation_weight: 1
description: "Academic and personal projects"
---

{% assign ordered_projects = site.projects | sort: 'ordering_weight' %}
{% for project in ordered_projects %}
## [{{ project.title }}]({{ project.url }})

{{ project.description }}

{% if project.image %} ![project.title]({{ project.image }}) {% endif %}

---

{% endfor %}