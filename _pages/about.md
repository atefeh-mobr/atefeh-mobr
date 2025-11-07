---
permalink: /
title: "Atefeh Mollabagher"
excerpt: "ECE Ph.D. student at UC San Diego"
toc: false
---

Hi! I am **Atefeh Mollabagher**, a Ph.D. student in Electrical and Computer Engineering at
[UC San Diego](https://ucsd.edu), advised by
[Dr. Parinaz Naghizadeh](https://parinazn.com).
Before that, I received my B.Sc. in Electrical Engineering from the
[University of Tehran](https://ece.ut.ac.ir/en).
My research focuses on recommender systems, multi agent reinforcement learning, and opinion dynamics.

✉️ atefeh@ucsd.edu


## Publications

{% include base_path %}
<ul class="archive">
{% assign recent = site.publications | sort: 'date' | reverse %}
{% for post in recent limit: 2 %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ul>

<p><a href="{{ '/publications/' | relative_url }}">See all publications →</a></p>
