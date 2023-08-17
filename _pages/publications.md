---
layout: page
permalink: /publications/
title: publications & talks
description: Publications by categories (articles, talks and thesis) and in reversed chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<h2>peer-reviewed articles</h2>

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

<h2>talks</h2>

<div class="publications">

{% bibliography --file talks %}

</div>

<h2>thesis</h2>

<div class="publications">

{% bibliography --file phdthesis %}

</div>
