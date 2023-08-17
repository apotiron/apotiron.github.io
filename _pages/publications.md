---
layout: page
permalink: /publications/
title: publications & talks
description: Publications by categories (articles, talks and thesis) and in reversed chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<h1>peer-reviewed articles</h1>

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

<h1>talks</h1>

<div class="publications">

{% bibliography --file talks %}

</div>

<h1>thesis</h1>

<div class="publications">

{% bibliography --file phdthesis %}

</div>
