---
layout: archive
title: "Selected Publications and Preprints"
permalink: /publications/
author_profile: true
---

<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">Full List of Pulications</a>

{% include base_path %}
# Federated & Transfer Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'FTL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
# Interpretable ML
{% for post in site.publications reversed %}
  {% if post.pubtype == 'XAI' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
# Missing Values
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MV' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
# Clinical Applications
{% for post in site.publications reversed %}
  {% if post.pubtype == 'APP' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
