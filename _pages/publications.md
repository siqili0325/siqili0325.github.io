---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>

Please find my up to date publications <a href="https://scholar.google.com/citations?user=n3zwPHkAAAAJ&hl=en">here</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
