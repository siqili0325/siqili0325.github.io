---
layout: archive
permalink: /publications/
author_profile: true
---

# Selected Publications

<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">A full list of publications available here.</a>
<br>
<br>

{% include base_path %}
<h2 style="color: #6495ED;">Federated & Transfer Learning</h2>

{% for post in site.publications reversed %}
  {% if post.pubtype == 'FTL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>
<h2 style="color: #6495ED;">Interpretable Machine Learning</h2>

{% for post in site.publications reversed %}
  {% if post.pubtype == 'XAI' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>

<h2 style="color: #6495ED;">Missing Values</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MV' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
<br>

<h2 style="color: #6495ED;">Biomedical & Clinical Applications</h2>

{% for post in site.publications reversed %}
  {% if post.pubtype == 'APP' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
