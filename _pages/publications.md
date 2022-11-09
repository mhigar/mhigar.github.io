---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

**Working Papers**
* _"Traffic Congestion and Labor Supply: Evidence from Smartphone data in Mexico"_ (Job Market Paper) <br />
    (presented at 2022 CREEA Annual Conference and TWEEDS 2022)
* _"Temperature, Work Time, and Intertemporal Labor Substitution: Evidence from Peru"_ <br />
    (previously circulated as _"Is it Too Hot to Work?"_ and presented at [EfD](https://efdinitiative.org/) Annual Meeting 2020, [SEEDS](http://www.sustainability-seeds.org/) Annual Workshop 2020, [CEA](https://www.economics.ca/cpages/home) 2021, [NAREA](http://www.narea.org/) 2021, and [CIREQ](https://www.cireqmontreal.com/) conference for climate change 2021).
    
    
**Work in Progress**
* _"COVID-19 and the Amazon Rainforest"_, with Jerico Fiestas and Javier Montoya. <br />
    (presented at 2022 COLCA SAEE conference)
* _"Migration and Environmental Quality: Evidence from Facebook data in Colombia"_, with Pablo Ordonez and Julieth Santamaria. <br />
    (presented at 2022 [AAEA](https://www.aaea.org/) Annual Meeting)
* _"Who work outdoors? Implication for Climate Change and Pandemics using Machine learning and text-as-data"_, with Jose Incio and Carlos Ospino.



**Journal Publications**
* _"The Persistent Effects of COVID-19 on Labor Outcomes: Evidence from Peru"_, forthcoming at _Applied Economics Letters_ (with Fernando Aragon and Carlos Ospino) [paper](https://www.tandfonline.com/eprint/ZEJY7UNFNQAUNRV9ABH9/full?target=10.1080/13504851.2022.2036319) - [working paper](https://ideas.repec.org/p/sfu/sfudps/dp21-10.html) <br />
<!--     (presented at [UNU-WIDER](https://www.wider.unu.edu/event/covid-19-and-development-effects-and-new-realities-global-south) Development Conference 2021) -->
    
    
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
