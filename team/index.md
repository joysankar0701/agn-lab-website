---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group != 'alum'" %}

{% include section.html %}
Past Members

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html %}

