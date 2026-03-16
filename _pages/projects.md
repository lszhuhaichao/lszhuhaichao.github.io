---
layout: single
title: "Projects"
permalink: /projects/
---

Projects are grouped into work I am actively pursuing and work that represents earlier phases.

{% assign project_docs = site.projects | sort: "date" | reverse %}

## Current Projects

{% for post in project_docs %}
{% if post.status == "current" %}
### [{{ post.title }}]({% if post.link %}{{ post.link }}{% else %}{{ post.url | relative_url }}{% endif %})

{{ post.excerpt }}
{% endif %}
{% endfor %}

## Past Projects

{% for post in project_docs %}
{% if post.status == "past" %}
### [{{ post.title }}]({% if post.link %}{{ post.link }}{% else %}{{ post.url | relative_url }}{% endif %})

{{ post.excerpt }}
{% endif %}
{% endfor %}
