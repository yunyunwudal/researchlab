---
title: Publications
nav:
  order: 2
  tooltip: Published works
---

## {% include icon.html icon="fa-solid fa-file-signature" %}Publications

You can find our publications on [Google Scholar](https://scholar.google.com/citations?user=3anVhr8AAAAJ&hl=en).

{% include section.html %}

## Highlighted
{%
  include list.html
  data="citations"
  component="citation"
  filters="group: featured"
  style="rich"
%}
{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="" %}
