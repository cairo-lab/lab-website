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

Resdents
{% include list.html data="members" component="portrait" filter="role == 'res'" %}

Students
{% include list.html data="members" component="portrait" filter="role == 'med'" %}

Collaborators
{% include list.html data="members" component="portrait" filter="role == 'collab'" %}
