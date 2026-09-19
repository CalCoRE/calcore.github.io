---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'alumni'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Our research is done in close partnership with school districts, teachers, and university researchers. We welcome inquiries from scholars, educators, and organizations interested in collaborating with us on learning sciences research and STEM design.

{% include section.html %}

{% include grid.html style="square" content=content %}
