---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our young vibrant team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html dark=true %}

Past Members

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html %}

