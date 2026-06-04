---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Harshinee _(her-she-knee)_. I am a Computer Science PhD Candidate at the University of British Columbia, Vancouver. I work with [Margo Seltzer](https://www.seltzer.com/margo/) and [Xin Tang](https://tangxinlab.org/).

I love building solutions that address real end-user pain points. I'm interested in solving problems across a variety of domains, including (but not limited to): Virtual Cells, Multimodal Learning (Video, Text, Gaze/Eye-Movements), Sparse Diagnostic Models, Interpretable and Explainable ML, and AI for Biology, Drug Discovery, and Diagnosis.


## Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
