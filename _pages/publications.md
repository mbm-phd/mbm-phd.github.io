---
layout: page
permalink: /publications/
title: Publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

  <!-- ==================== JOURNAL ARTICLES ==================== -->

  <h2 class="bibliography">Journal Articles</h2>

  {% bibliography --query @article %}


  <!-- ==================== CONFERENCE ==================== -->

  <h2 class="bibliography">Conference</h2>

  {% bibliography --query @misc %}


  <!-- ==================== BOOKS ==================== -->

  <h2 class="bibliography">Books</h2>

  {% bibliography --query @book %}

</div>
