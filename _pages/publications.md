---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

**Working Papers**
* _"Traffic Congestion and Labor Supply: Evidence from Smartphone data in Mexico"_ <br />
    (presented at 2022 CREEA Annual Conference, TWEEDS 2022, PacDev 2023, [2023 AERE Summer Conference](https://www.aere.org/aere-summer-conference), [2023 Emerging Mobility Scholars Conference](https://positivezero.civmin.utoronto.ca/travel-to-toronto/), [20th International Economic Association World Congress](https://ieawc2023.org/), and the [2023 LACEA and LAMES Conference](https://www.lacealames2023.org/))
    <details>
      <summary>Abstract</summary>
  
      Does traffic congestion affect time allocation? I use highly granular smartphone data from Mexico City to study empirically how traffic congestion affects work-       time allocation. I find that traffic increases hours worked. The effect is driven by workers leaving work later, not by changes in arrival time. There is modest       evidence that labor income does not increase although total hours do. These results highlight an avoidance mechanism consistent with bottleneck models that has been overlooked when estimating the costs of congestion. 
    </details>
    
* _"Is it Too Hot to Work? Evidence from Peru"_ (_Revise and Resubmit_)
    <details>
      <summary>Abstract</summary>
  
      Will raising temperatures due to climate change affect labor markets? This paper studies the effect of temperature on hours worked using panel data for Peru           from 2007-2015. I combine hours worked from household surveys with reanalysis and satellite weather data. I find evidence that hours worked are negatively             affected by hot temperatures. This effect is driven by informal jobs instead of jobs in industries highly exposed to the weather. These results suggest that           labor market segmentation may play a role in the impacts of climate change on labor market outcomes in developing countries.
    </details>    

**Work in Progress**
* _"Migration and Environmental Quality: Evidence from Facebook data in Colombia"_, with Pablo Ordonez and Julieth Santamaria. <br />
    (presented at 2022 [AAEA](https://www.aaea.org/) Annual Meeting)
    <details>
      <summary>Abstract</summary>
  
      How would the projected massive migration to cities in the developing world impact the environment? We study the effect of urban growth on air pollution using         the exogenous Venezuelan diaspora to Colombia. We track migrants using the Facebook logins of users who created an account in Venezuela and are currently in           Colombia. Using a difference-in-difference approach and an instrumental variable approach, we find that migration increases PM 2.5. This result highlights the         need for labor market policies that allow newcomers to relocate to less polluting industries.
    </details>     
    
* _"Who work outdoors? Using Machine Learning, Text-as-Data, and Large Language Models (LLMs)"_, with Jose Incio and Carlos Ospino.


**Journal Publications**

<ol>
  <li value="2">
    <em>"COVID-19 and the Amazon Rainforest: impacts, CO2 emissions, and social cost"</em>, 
    <em>Trees, Forest and People</em>, Volume 20, 2025 
    (with Jerico Fiestas and Javier Montoya) 
    <a href="https://doi.org/10.1016/j.tfp.2025.100888">paper</a>
    <!-- <details>
      <summary>Abstract</summary>
      We leverage spatial variation in the severity of the COVID-19 pandemic across Peru to examine its impacts on deforestation...
    </details> -->
  </li>
    
    <br> <!-- adds space between the items -->
    
  <li value="1">
    <em>"The Persistent Effects of COVID-19 on Labor Outcomes: Evidence from Peru"</em>, 
    <em>Applied Economics Letters</em>, 30:8, 1065–1076, 2023 
    (with Fernando Aragon and Carlos Ospino) 
    <a href="https://www.tandfonline.com/eprint/ZEJY7UNFNQAUNRV9ABH9/full?target=10.1080/13504851.2022.2036319">paper</a> - 
    <a href="https://ideas.repec.org/p/sfu/sfudps/dp21-10.html">working paper</a>
  </li>
</ol>

<!-- 2. _"COVID-19 and the Amazon Rainforest: impacts, CO2 emissions, and social cost"_,_Trees, Forest and People_ Volume 20, 2025 (with Jerico Fiestas and Javier Montoya [paper](https://doi.org/10.1016/j.tfp.2025.100888). 
     <details>
      <summary>Abstract</summary>
  
      We leverage spatial variation in the severity of the COVID-19 pandemic across Peru to examine its impacts on deforestation. We find that COVID-19 explains one-third of the deforestation increase in 2020. We estimate that a 10% increase in COVID-19 cases increases deforestation by 1.5%. This impact is exacerbated in districts with coca production or illegal mining. Pandemic-driven deforestation increased CO2 emissions by over 8 million tons, representing a social cost five times the national budget for forest management. These findings underscore the vulnerability of environmental monitoring and enforcement to external shocks in developing countries. 
    </details>  
   
1. _"The Persistent Effects of COVID-19 on Labor Outcomes: Evidence from Peru"_, _Applied Economics Letters_ 30:8, 1065-1076, 2023 (with Fernando Aragon and Carlos Ospino) [paper](https://www.tandfonline.com/eprint/ZEJY7UNFNQAUNRV9ABH9/full?target=10.1080/13504851.2022.2036319) - [working paper](https://ideas.repec.org/p/sfu/sfudps/dp21-10.html) <br />
<!--     (presented at [UNU-WIDER](https://www.wider.unu.edu/event/covid-19-and-development-effects-and-new-realities-global-south) Development Conference 2021) --> -->


    
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
