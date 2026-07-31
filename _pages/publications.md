---
layout: page
permalink: /publications/
title: Publications
description: EPOCHS collaboration publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<details open>
  <summary><strong>EPOCHS-DR1 series</strong></summary>
  {% bibliography --query @*[keywords ~= EPOCHS-DR1] %}
</details>

<!-- <details>
  <summary><strong>EPOCHS-DR2</strong></summary>
  {% bibliography --query @*[keywords=/EPOCHS-DR2/] %}
</details> -->

<details>
  <summary><strong>Non-EPOCHS series collaboration papers</strong></summary>
  {% bibliography --query @*[keywords ~= Non-EPOCHS] %}
</details>

</div>
