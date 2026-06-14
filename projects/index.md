---
title: Projects
nav:
  order: 2
  tooltip: Lab projects and resources
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects translate research ideas into experiments, prototypes, datasets, software tools, and educational resources. This page is intended to grow with the lab as projects mature from early concepts into publishable and reusable work.

{% include tags.html tags="publication, resource, software, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Additional Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
