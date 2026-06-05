---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Harshinee (her-she-knee). I am a Computer Science PhD Candidate at the University of British Columbia, Vancouver, where I'm fortunate to work with [Margo Seltzer](https://www.seltzer.com/margo/) and [Xin Tang](https://tangxinlab.org/). At my core, I love solving problems and building things. My PhD thesis focuses on AI for Alzheimer's Disease diagnosis, but my research footprint spans both academia (User Personalization, eXplainable AI) and industry (Computer-Use Agentic Workflows, AI for Knowledge Discovery).

I’m deeply committed to lifting up the scientific community. I've built open-source, cloud-powered prototypes for community challenges and designed Quantum Computing educational materials to make the field accessible to kids. I'm interested in solving problems across a variety of domains, including (but never limited to): Virtual Cells, Multimodal Learning (Video, Text, Gaze/Eye-Movements), Sparse Diagnostic Models, Interpretable and Explainable ML, and AI for Biology, Drug Discovery, and Diagnosis.

And, when I have the time, I write for the soul to keep myself grounded.

## Research Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
