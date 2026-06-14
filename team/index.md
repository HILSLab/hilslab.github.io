---
title: Team
nav:
  order: 3
  tooltip: Lab members and collaborators
---

# {% include icon.html icon="fa-solid fa-users" %}Team

HILSLab is building a collaborative research group in the Department of Mechanical and Aerospace Engineering at the University at Buffalo. The team brings together students, researchers, and collaborators interested in human-centered robotics, autonomy, controls, and engineered systems.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

We welcome motivated students who are interested in rigorous experiments, careful modeling, readable code, and research that keeps human needs visible in the design of complex systems.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
