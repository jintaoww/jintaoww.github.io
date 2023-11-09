---
layout: archive
title: " "
permalink: /research/
author_profile: false
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Research Projects  

- **Jan. 2023 - Present**: "AI-Driven Intelligent 6G Wireless Communications: Theory and Technology"  

     Funded by NSFC and FDCT under Grant 0087/2022/AFJ.  

     *Student Investigator*, in charge of the design of transceiver, beamforming and prototype realization.


- **Oct. 2020 - Sep. 2022**: Analysis and Optimal Design of Simultaneous Wireless Information and Power Transfer in IoT Networks  

     Funded by FDCT under Grant  0036/2019/A1.  

     *Student investigator*, in charge of the prototype verification of wireless information and energy transmission based on NI USRP.