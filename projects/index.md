---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

In addition to publishing our findings in peer-reviewed journals, we maintain open-source software called [CHEEREIO](https://cheere.io) used by research groups around the world to quantify emissions of greenhouse gases and air pollutants. We also publish large high resolution pollution maps for use in public health studies, regulation, and other applications. See below for our projects.

{% include tags.html tags="resource, software" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
