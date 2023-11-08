---
layout: archive
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Selected Publications
<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">A full list of publications available here.</a>
<br>
### Federated & Transfer Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'FTL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
### Interpretable Machine Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'XAI' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
### Missing Values
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MV' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
### Biomedical & Clinical Applications
{% for post in site.publications reversed %}
  {% if post.pubtype == 'APP' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
