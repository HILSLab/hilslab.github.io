---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For questions about research, collaboration, or student opportunities, contact the Human in the Loop Systems Laboratory at the University at Buffalo.

{%
  include button.html
  type="email"
  text="hilslab@buffalo.edu"
  link="hilslab@buffalo.edu"
%}
{%
  include button.html
  type="address"
  text="University at Buffalo"
  tooltip="University at Buffalo campus map"
  link="https://www.buffalo.edu/home/visiting-ub/CampusMaps.html"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Mechanical and Aerospace Engineering"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="University at Buffalo"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Human in the Loop Systems Laboratory<br>
Department of Mechanical and Aerospace Engineering<br>
University at Buffalo
{% endcapture %}

{% capture col2 %}
Research areas<br>
Human-machine interaction<br>
Robotics, autonomy, and mechanical systems
{% endcapture %}

{% capture col3 %}
Contact<br>
hilslab@buffalo.edu<br>
Buffalo, New York
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
