---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
Below are my research works, grouped by field.

<div class="publications">
<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
  Mathematical Relativity
</div>
{% bibliography --query @article[field=GR]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
  Inverse Problems
</div>
{% bibliography --query @article[field=IP]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
  Particle Physics
</div>
{% bibliography --query @article[field=PP]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
  Chemical Engineering
</div>
{% bibliography --query @article[field=CE]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
Books
</div>
{% bibliography --query @article[field=book]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
Master Thesis
</div>
{% bibliography --query @mastersthesis[field=GR]* %}
</div>
