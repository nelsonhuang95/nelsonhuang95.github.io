---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


The full list of my publications can be found in <u><a href="https://scholar.google.com/citations?user=CG6rNcwAAAAJ">Google Scholar</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include publications.html %}
{% endfor %}
