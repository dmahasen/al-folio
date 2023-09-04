---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @*[eprint=false]   %}


</div>

## Working papers 
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @*[tec=true]    %}

</div>



