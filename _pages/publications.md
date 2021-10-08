---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---


**Work in Progress**

* _"Congestion and Labor Supply: Evidence from Smartphone data in Mexico"_
* _"Who work outdoors? Implication for Climate Change and Pandemics using Machine Learning"_, with Daniel Jimenez and Carlos Ospino.
* _"Migration and Environmental Quality: Evidence from Facebook data in Colombia"_, with Pablo Ordonez and Julieth Santamaria.


**Working Papers**

* _"Temperature, Work Time, and Intertemporal Labor Substitution: Evidence from Peru"_
* _"The persistent effects of COVID-19 on labor outcomes: evidence from Peru"_, with Fernando Aragon and Carlos Ospino (Submitted)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
