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
<h2>Mathematical Relavitiy</h2>
{% bibliography --query @article[field=GR]* %}

<h2>Inverse Problems</h2>
{% bibliography --query @article[field=IP]* %}

<h2>Particle Physics</h2>
{% bibliography --query @article[field=PP]* %}

<h2>Chemical Engineering</h2>
{% bibliography --query @article[field=CE]* %}

<h2>Books</h2>
{% bibliography --query @book[field=IP]* %}

<h2>Master Thesis</h2>
{% bibliography --query @mastersthesis[field=GR]* %}

</div>
