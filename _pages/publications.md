---
layout: page
permalink: /publications/
#title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Journal Publications

<div class="publications">
  {% bibliography --file journal %}
</div>

## Conference Publications

<div class="publications">
  {% bibliography --file conference %}
</div>

## Thesis

<div class="publications">
  {% bibliography --file thesis %}
</div>

## Preprints

<div class="publications">
  {% bibliography --file preprint %}
</div>
