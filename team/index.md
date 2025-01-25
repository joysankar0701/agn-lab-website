---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}
PI

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" filter="group != 'alum'" %}

{% include section.html %}
Current Members

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" filter="group != 'alum'" %}

{% include section.html %}
Past Members

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html %}

