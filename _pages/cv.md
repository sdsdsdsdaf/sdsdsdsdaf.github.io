---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Artificial Intelligence, Gachon University, 2021 – 2027 (expected)
  * Advisors: Prof. Jungchan Cho, Prof. Ilchae Jung

Research Interests
======
* Sparse Autoencoders
* Interpretability
* Computer Vision
* Large Language Models

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
