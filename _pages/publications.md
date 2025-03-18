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

## <span style="color:red; text-align:center; display:block;">Conference Publications</span>

<div class="publications">
  {% bibliography --file conference %}
</div>

## <span style="color:red; text-align:center; display:block;">Journal Publications</span>

<div class="publications">
  {% bibliography --file journal %}
</div>

## <span style="color:red; text-align:center; display:block;">Thesis</span>

<div class="publications">
  {% bibliography --file thesis %}
</div>

## <span style="color:red; text-align:center; display:block;">Preprints</span>

<div class="publications">
  {% bibliography --file preprint %}
</div>
