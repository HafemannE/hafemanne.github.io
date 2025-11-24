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
### Mathematical Relavitiy
**In preparation**
<div class="publications">
{% bibliography --query @unpublished[field=GR]* %}
</div>

**Published**
<div class="publications">
{% bibliography --query @article[field=GR]* %}
</div>

---

### Inverse Problems

<div class="publications">
{% bibliography --query @article[field=IP]* %}
</div>

---

### Particle Physics
<div class="publications">
{% bibliography --query @article[field=PP]* %}
</div>

---
### Chemical Engineering

<div class="publications">
{% bibliography --query @article[field=CE]* %}
</div>

---

### Books

<div class="publications">
{% bibliography --query @book[field=IP]* %}
</div>

---

### Master thesis
<div class="publications">
{% bibliography --query @mastersthesis[field=GR]* %}
</div>