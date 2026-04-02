---
layout: single
title: "Notes"
permalink: /notes/
---

Short technical writing on systems, perception, benchmarking, and agentic engineering.

{% assign note_docs = site.notes | sort: "date" | reverse %}

{% for post in note_docs %}
### [{{ post.title }}]({{ post.url | relative_url }})

{% if post.excerpt %}{{ post.excerpt }}{% endif %}

{% endfor %}
