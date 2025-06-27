---
layout: archive
title: ""
permalink: /
# excerpt: "About me"
author_profile: true
#redirect_from: 
#  - /about/
#  - /about.html
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**<font color=Fuchsia>Hello, welcome! </font>**
# About Me
**Jintao Wang** received the B.Eng. in 2020 in communication engineering from *Jilin University* , Changchun, China. He received the Ph.D. degree in 2024 in Electrical and Computer Engineering from *University of Macau*, Macau, China. 

He is currently a **Post-doctoral Fellow** with the State Key Laboratory of Internet of Things for Smart City (SKL-IOTSC), *University of Macau*. His main research interests aim for the physical layer transmission technology for next-generation wireless communications, including massive MIMO, reconfigurable intelligent surface (RIS), integrated sensing and communication (ISAC), mmWave communication, transceiver design, hardware impairments, convex optimization , and wireless communication prototype.


# Contact
**Email:** <wang.jintao@connect.um.edu.mo> or <jintaowang@um.edu.mo>  

**Address:** Room 5004, Building N21, University of Macau, Avendia da Universidade, Taipa, Macao SAR, China


<body>
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=0e1633&w=a&t=tt&d=eaDNHe07DDvU8-ERxcx4XBalmsAS-BHZbz2OnbQyz74&co=0b4975&cmo=3acc3a&cmn=ff5353&ct=cdd4d9'></script>
</body>