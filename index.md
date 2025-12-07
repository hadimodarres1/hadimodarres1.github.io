---
layout: collection
author_profile: true
entries_layout: grid
classes: wide

---

I am a Principal Data Scientist at NHS England, where we develop and deploy data science products to make a positive impact on NHS patients and workforce. Previously I worked in a medical device start up, and deployed machine learning algorithms for earlier detection of cognitive impairment. I have also worked as a data analytics consultant, delivering analytical products for clients. 

I received my PhD in Engineering from the University of Cambridge. My research focused on using nanotechnology for lithium ion batteries. I always enjoyed working with and discovering new insights from data which led me to a career in data science. 

Below you will find examples of some of the projects from my recent work and PhD.

{% assign items = site.projects | sort: "order" %}

<div class="entries-grid">
  {% include documents-collection.html entries=items type="grid" %}
</div>

