---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications in reverse chronological order. Full list on Google Scholar.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Preprints and under review</h2>
{% bibliography --query @*[status=preprint] --group_by none %}

<h2 class="bibliography">Published</h2>
{% bibliography --query @*[status!=preprint] %}

</div>
