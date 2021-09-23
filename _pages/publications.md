---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

**Summary**: My research interests are algorithm design and implementation for wireless networks. I’m particularly interested in the following two aeras:
- Handling uncertainty: Provide probabilistic guanratees in presense of random network parameters without distribution knowledge. E.g., Provide probabilistic interference threshold guarantee using the mean and covariance of random channcel gains.
- Real-time algorithm: Meet wall-clock timing requirement. E.g., 125 $\mu$s (one TTI in 5G-NR numerology 3) timing requiremnt for a scheduling and power control algoriothm.

I also closely collaborate with my colleagues to work on Age of Information, MIMO, Faster-than-Nyquist (FTN) systems. In 2019, I received the Fred W. Ellersick MILCOM Award for the Best Paper in the unclassified technical program. You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=utvZzaAAAAAJ&hl=en).

## **First-authored:**

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## **Co-authored:**

{% include base_path %}

{% for post in site.publicationscoauthor reversed %}
  {% include archive-single.html %}
{% endfor %}
