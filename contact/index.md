---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Good science isn't solitary task. Please reach out.

{%
  include button.html
  type="email"
  text="brandon@cairo-lab.org"
  link="brandon@cairo-lab.org"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/DJ5BeJQgQPdkJHHB7"
%}

{% include section.html %}


{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
# footer text col 1
{% endcapture %}

{% capture col2 %}
# footer text col 2
{% endcapture %}

{% capture col3 %}
# footer text col 3
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
