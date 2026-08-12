---
layout: archive
title: "Open Problems"
permalink: /open-problems/
author_profile: true
---

These problems are open on this site, meaning that I have not yet found a complete proof or definitive answer.

{% assign open_posts = site.posts | where: "status", "open" %}

{% if open_posts.size > 0 %}
  {% include documents-collection.html entries=open_posts type="list" %}
{% else %}
  There are no open problems at the moment.
{% endif %}
