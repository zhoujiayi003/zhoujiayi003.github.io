---
layout: page
permalink: /publications/
title: publications
description: grouped by authorship role. <sup>*</sup> denotes equal contribution.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<h2>First author / co-first author</h2>

{% bibliography --query @*[first_author=true] %}

<h2>Second author / other</h2>

{% bibliography --query @*[first_author!=true] %}

</div>
