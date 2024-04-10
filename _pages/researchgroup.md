---
layout: archive
title: "Environment and Transportation Research Group"
permalink: /researchgroup/
author_profile: false
---
{% assign link = permalink %}
<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="site-nav" class="greedy-nav">
        <button><div class="navicon"></div></button>
        <ul class="lista">
            <li class="researchgroup__menu-item"><a href="{{ base_path }}{{link}}">ABOUT</a></li>
            <li class="researchgroup__menu-item"><a href="{{ base_path }}/research"> RESEARCH </a> </li>        
            <li class="researchgroup__menu-item"><a href="{{ base_path }}/team"> TEAM </a> </li>         
        </ul>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>

{% include archive-single.html %}
{% include base_path %}

