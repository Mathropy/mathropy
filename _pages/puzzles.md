---
layout: archive
title: "Puzzles"
permalink: /puzzles/
author_profile: true
---

Browse all mathematical puzzles by Mathropy.

**Statuses:** Solved means a full solution is available; Partial means the result is known but the proof is incomplete; Open means no definitive answer is known yet.

[Browse by tag]({{ '/tags/' | relative_url }})

{% assign puzzles = site.posts %}
{% include documents-collection.html entries=puzzles type="list" %}
