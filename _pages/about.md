---
permalink: /
title: "Sung-Feng Huang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
======
Sung-Feng Huang is a Research Scientist at NVIDIA Research Taiwan. His research focuses on generative AI for speech and audio, with expertise in speech recognition, synthesis, separation, and machine learning techniques such as self-supervised and meta learning.

He received his Ph.D. from National Taiwan University, where he was co-advised by Prof. Lin-shan Lee and Prof. Hung-yi Lee. During his doctoral studies, he worked extensively on advanced speech processing technologies and machine learning methodologies, contributing to the development of innovative AI-driven audio applications.

Before joining NVIDIA as a full-time Research Scientist, Sung-Feng interned with the same research team, where he gained hands-on experience in cutting-edge AI research. Now, he is dedicated to advancing generative AI in speech and audio, driving new possibilities in human-computer interaction and audio-based AI systems.

Publications
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %} -->
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Research Experiences
======
