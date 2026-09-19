---
title: Projects
nav:
  order: 2
  tooltip: More about our work
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% comment %}
{% include tags.html tags="publication, resource, website" %}*/
{% endcomment %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
