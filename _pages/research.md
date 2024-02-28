---
layout: archive
title: " "
permalink: /research/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





# Work

**Research**

  - To be updated... 


**Intern as the application engineer**

  - FPGA development for TDD switching of millimeter-wave frequency converter based on LTE frame structure with LABVIEW NXG.
  - Serial beam control of various millimeter wave antenna arrays based on Labview NXG.


# Demos  

### Demo1: **RDARS for Localization**  
  - Title: Reconfigurable Distributed Antennas and Reflecting Surface (RDARS)-Aided Integrated Sensing and Communication   
     ![RDARS-Platform](/images/RDARS-Platform.png)

  - Description: The RDARS, a flexible and reconfigurable combination of distributed antennas and reflecting surface, 
is introduced to achieve the ISAC dual functionalities with only the communication signal. The developed RDARS-aided ISAC prototype achieves reliable user localization without compromising communication performance with beam scanning and range estimation.

### Demo2: **Vision-aided Multi-user Sensing and Communications**
  - Title: Vision-aided Multi-user Beam Training and Tracking for mmWave Massive MIMO Communications  
     ![Vision-Platform](/images/Vision-Plateform.png)

  - Description: We propose a novel vision-based framework that integrates visual data taken by a camera at the base station, to assist in the practical multi-user beam training and tracking. The vision-aided mmWave massive MIMO prototype achieves fast multi-user network access and reliable multi-user mobile communications, laying the foundation for scaling vision-aided wireless communication applications to real-world 6G scenarios and practical implementations.







# Research Projects  

- **Jan. 2023 - Present**: "AI-Driven Intelligent 6G Wireless Communications: Theory and Technology"  

     Funded by NSFC and FDCT under Grant 0087/2022/AFJ.  

     *Student Investigator*, in charge of the design of transceiver, beamforming and prototype realization.  



- **Oct. 2020 - Sep. 2022**: Analysis and Optimal Design of Simultaneous Wireless Information and Power Transfer in IoT Networks  

     Funded by FDCT under Grant  0036/2019/A1.  

     *Student investigator*, in charge of the prototype verification of wireless information and energy transmission based on NI USRP.  


# Hardware Resources of the Group

  ![Hardware-Platform](/images/Platform.png)
















