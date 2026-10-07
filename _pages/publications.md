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
<ul style="padding-left: 0; margin-left: 0; "><li>Mathematical Relativity</li></ul>
</div>
{% bibliography --query @article[field=GR]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
<ul style="padding-left: 0; margin-left: 0; "><li>Inverse Problems</li></ul>
</div>
{% bibliography --query @article[field=IP]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
<ul style="padding-left: 0; margin-left: 0; "><li>Particle Physics</li></ul>
</div>
{% bibliography --query @article[field=PP]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
<ul style="padding-left: 0; margin-left: 0; "><li>Chemical Engineering</li></ul>
</div>
{% bibliography --query @article[field=CE]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
<ul style="padding-left: 0; margin-left: 0; "><li>Books</li></ul>
</div>
{% bibliography --query @article[field=book]* %}

<div style="font-weight:500; font-size:1.0rem; margin-top:2rem; margin-bottom:0rem;">
<ul style="padding-left: 0; margin-left: 0; "><li>Master Thesis</li></ul>
</div>
{% bibliography --query @mastersthesis[field=GR]* %}
</div>
