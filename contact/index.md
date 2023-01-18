---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is located on campus at The Land Institute just outstide of Salina, Kansas. Stop by sometime to see what we are up to.

{%
  include link.html
  type="email"
  icon=""
  text="Email"
  tooltip="Get in touch with us"
  link="schlautman@landinstitute.org"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(785) 823-5376"
  tooltip="Phone Number"
  link="+1-785-823-5376"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/ozZXBisVSP2MADY98"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

The Land Institute
2440 E Water Well Rd
Salina, Kansas 67401 
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Legume Lab at The Land Institute"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Legume Lab"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
