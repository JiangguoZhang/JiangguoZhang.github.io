---
layout: archive
title: "Membrane contact probability: An essential and predictive character for the structural and functional studies of membrane proteins"
permalink: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009972
author_profile: true
---

---
layout: archive
title: "Quantification of Myxococcus xanthus Aggregation and Rippling Behaviors: Deep-learning Transformation of Phase-contrast into Fluorescence Microscopy Images"
permalink: https://www.mdpi.com/2076-2607/9/9/1954
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=KCrsvKIAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
