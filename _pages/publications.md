---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=eaQMdjsAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</u>
{% endif %}

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=eaQMdjsAAAAJ&hl=en&oi=ao)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Miscellaneous

{% for post in site.misc reversed %}
  {% include archive-single.html %}
{% endfor %}