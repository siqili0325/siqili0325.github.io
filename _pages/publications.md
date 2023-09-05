---
layout: archive
title: "Selected Publications and Preprints"
permalink: /publications/
author_profile: true
---


<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">Full List of Pulications</a>

{% include base_path %}

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Federated & Transfer Learning</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'FTL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Interpretable ML</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'XAI' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Missing Values</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MV' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Clinical Applications</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'APP' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
