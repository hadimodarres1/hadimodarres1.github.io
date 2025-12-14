---
layout: collection
author_profile: true
entries_layout: grid
classes: wide

---

I’m a Principal Data Scientist at NHS England, where I work on building and deploying machine learning models using large-scale healthcare data to support earlier diagnosis, service planning, and better outcomes for patients and the NHS workforce. My work focuses on developing end-to-end, reproducible data science pipelines and interpretable models that can be used in real operational settings.

Before joining NHS England, I led data science work at a medical device start-up developing AI tools for detecting cognitive impairment, and earlier worked as an analytics consultant across a range of sectors. I have a PhD in Engineering from the University of Cambridge, and my background spans academic research, healthcare, and applied machine learning. Below you will find examples of some of the projects from my recent work and PhD.

{% assign items = site.projects | sort: "order" %}

<div class="entries-grid">
  {% include documents-collection.html entries=items type="grid" %}
</div>

