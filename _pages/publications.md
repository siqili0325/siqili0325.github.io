---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---

<a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">Google Scholar Profile</a>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
