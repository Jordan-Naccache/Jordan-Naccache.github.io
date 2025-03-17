---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## <div style="color:red; text-align:center;">Conference Publications</div>

<div class="publications">
  {% bibliography --file conference %}
</div>

## <div style="color:red; text-align:center;">Journal Publications</div>

<div class="publications">
  {% bibliography --file journal %}
</div>

## <div style="color:red; text-align:center;">Thesis</div>

<div class="publications">
  {% bibliography --file thesis %}
</div>

## <div style="color:red; text-align:center;">Preprints</div>

<div class="publications">
  {% bibliography --file preprint %}
</div>
