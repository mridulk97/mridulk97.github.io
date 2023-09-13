---
layout: page
permalink: /publications/
title: Publications
description: #Publications are listed according to their type and in reverse chronological order
nav: true
nav_order: 1
---
<!-- To add from a separate file just use:  bibliography --file preprint  -->
<!-- _pages/publications.md -->

<div class="publications">
  <p>
    Publications are listed according to their type and in reverse chronological order.
    For an updated list please check on
    <a href="https://scholar.google.com/citations?user=AEer2h4AAAAJ&hl=en">Google Scholar</a>.
    * denotes equal contribution
  </p>  

{% bibliography -f {{ site.scholar.bibliography }} %}
</div>
