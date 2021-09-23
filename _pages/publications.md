---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## **Summary** 

My research interests are algorithm design and implementation for wireless networks. I’m particularly interested in the following two aeras:
- Handling uncertainty: Provide probabilistic guanratees in presense of random network parameters without distribution knowledge. E.g., Provide probabilistic interference threshold guarantee using the mean and covariance of random channcel gains.
- Real-time algorithm: Meet wall-clock timing requirement. E.g., 125 $\mu$s (one TTI in 5G-NR numerology 3) timing requiremnt for a scheduling and power control algoriothm.

I also closely collaborate with my colleagues to work on Age of Information, MIMO, Faster-than-Nyquist (FTN) systems. In 2019, I received the Fred W. Ellersick MILCOM Award for the Best Paper in the unclassified technical program. You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=utvZzaAAAAAJ&hl=en).

## **First-authored**

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## **Co-authored**

- "On scheduling with AoI violation tolerance", published in _IEEE INFOCOM_, 2021
- "Minimizing AoI in a 5G-based IoT Network under Varying Channel Conditions", published in _IEEE Internet of Things Journal_, 2021
- "AoI Scheduling with Maximum Thresholds", published in _IEEE INFOCOM_, 2020
- "GPU: A New Enabling Platform for Real-Time Optimization in Wireless Networks", published in _IEEE Network_, 2020
- "A deep-reinforcement-learning-based approach to dynamic eMBB/URLLC multiplexing in 5G NR", published in _IEEE Internet of Things Journal_, 2020
- "Minimizing age of information under general models for IoT data collection", published in _IEEE Transactions on Network Science and Engineering_, 2019
- "A general model for minimizing age of information at network edge", published in _IEEE INFOCOM_, 2019
- "To cancel or not to cancel: Exploiting interference signal strength in the eigenspace for efficient MIMO DoF utilization", published in _IEEE INFOCOM_, 2019
- "GPF: A GPU-based Design to Achieve $\sim$100 $\mu$s Scheduling for 5G NR", published in _ACM MobiCom_, 2018
- "A self-adaptive algorithm of carrier frequency offset estimate in wireless network", published in _IEEE ICCWAMTIP_, 2015
