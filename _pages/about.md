---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Harshinee (her-she-knee). I'm a Computer Science PhD Candidate at the University of British Columbia, Vancouver, where I am co-advised by [Margo Seltzer](https://www.seltzer.com/margo/) and [Xin Tang](https://tangxinlab.org/), and have previously collaborated with [Cristina Conati](https://www.cs.ubc.ca/people/cristina-conati).

Within academia, my PhD thesis focuses on AI for Alzheimer’s disease diagnosis and drug discovery, and I've also driven research in user personalization and eXplainable AI (XAI). On the industry side, I've worked on research problems involving LLM evaluations and benchmarking, computer-use agentic workflows, and AI for knowledge discovery.

I’m deeply committed to lifting up the scientific community and giving back whenever I can. I've built open-source, cloud-powered prototypes for community-facing challenges and designed quantum computing educational materials to make the field accessible to children.

When I have the time, I also write for myself.

## Research Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
