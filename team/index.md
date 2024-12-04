---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Labs are fluid groups, but our work wouldn't have been possible without these folks.

{% include section.html %}

Lab Founders
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

Lab Contributors 
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.svg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
