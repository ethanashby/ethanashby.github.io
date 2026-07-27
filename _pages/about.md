---
permalink: /
title: "Research Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is Ethan Ashby's research website. I am a Statistician in the Early Development Biometrics group at Genentech. I earned my PhD from the Department of Biostatistics at the University of Washington, where my research focused on developing statistical methods to evaluate vaccine effectiveness. My research was supported financially through the NSF Graduate Research Fellowship Grant. I also graduated with a BA in Mathematics from Pomona College. 

I am broadly interested in the statistics for clinical trials, causal inference, survival analysis, treatment effect heterogeneity, and causal interference.

## Highlights

{% include base_path %}

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}