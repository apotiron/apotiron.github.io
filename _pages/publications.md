---
layout: page
permalink: /publications/
title: publications & talks
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

## peer-reviewed articles

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

## talks

<div class="publications">

{% bibliography --file talks %}

</div>

## thesis

<div class="publications">

{% bibliography --file phdthesis %}

</div>
