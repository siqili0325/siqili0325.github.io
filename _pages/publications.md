---
layout: archive
permalink: /publications/
author_profile: true
---

<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">A full list of publications available here.</a>
<br>
<br>
{% include base_path %}
## Federated & Transfer Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'FTL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>
## Interpretable Machine Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'XAI' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>
## Missing Values
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MV' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>
## Biomedical & Clinical Applications
{% for post in site.publications reversed %}
  {% if post.pubtype == 'APP' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
