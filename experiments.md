---
layout: page
title: Experiments
---

<!-- Automatic project list generator -->

{% for project in site.data.projects %}
<div class="toc">
  <img src="{{ project.avatar }}" class="avatar" />
  <a href="{{ project.url }}">{{ project.title }}</a>
  <p>{{ project.snippet }}</p>
</div>
{% endfor %}

## Experiments and projects at other institutions

### NYPL (New York Public Library) Labs
- [**Public Domain Collections**](https://www.nypl.org/research/collections/digital-collections/public-domain): More than 180,000 items in the NYPL's Digital Collections are in the Public Domain and have been made available for download, remixes, and these impressive [visualizations](http://publicdomain.nypl.org/pd-visualization/).
- The NYPL Labs did many other ambitious [projects](https://www.nypl.org/blog/2014/09/03/generative-ebook-covers), several of which used data from their extensive digital collections.

### Yale University Library Digital Humanities Lab
- [Photogrammar](http://photogrammar.yale.edu/): A web-based platform for organizing, searching and visualizing the 170,000 photographs created by the United States Farm Security Administration and Office of War Information (FSA-OWI) from 1935–1945.
- [Neural Neighbors](https://yaledhlab.github.io/neural-neighbors/): A project underway to "enable users to identify visual similarity at scale across collections of photographs and videos," focused on the Beinecke Library's vast Meserve-Kunhardt Collection of nineteenth-century photographs.
