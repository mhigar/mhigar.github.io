---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---


**Work in Progress**

* _"Congestion and Labor Supply: Evidence from Smartphone big data in Mexico"_
* _"Who work outdoors? Implication for Climate Change and Pandemics using Machine Learning"_, with Daniel Jimenez and Carlos Ospino.
* _"Migration and Environmental Quality: Evidence from Facebook data in Colombia"_, with Pablo Ordonez and Julieth Santamaria.


**Working Papers**

* _"Temperature, Work Time, and Intertemporal Labor Substitution: Evidence from Peru"_ <br />
    (previously circulated as _"Is it Too Hot to Work?"_ and presented at [EfD](https://efdinitiative.org/) Annual Meeting 2020, [SEEDS](http://www.sustainability-seeds.org/) Annual Workshop 2020, [CEA](https://www.economics.ca/cpages/home) 2021, [NAREA](http://www.narea.org/) 2021, and [CIREQ](https://www.cireqmontreal.com/) conference for climate change 2021).
* _["The persistent effects of COVID-19 on labor outcomes: evidence from Peru"](https://ideas.repec.org/p/sfu/sfudps/dp21-10.html)_, with Fernando Aragon and Carlos Ospino (_Revise and Resubmit_) <br />
    (presented at [UNU-WIDER](https://www.wider.unu.edu/event/covid-19-and-development-effects-and-new-realities-global-south) Development Conference 2021)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
