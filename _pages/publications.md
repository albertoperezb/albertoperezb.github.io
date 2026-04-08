---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 2
---

<!-- Publications -->
<div class="publications">
  <h2 class="bibliography-title">Publications</h2>
  {% bibliography --query @article %}
</div>

<!-- Working Papers -->
<div class="publications">
  <h2 class="bibliography-title">Working papers</h2>
  {% bibliography --query @unpublished[note!=Work in Progress] %}
</div>

<!-- Work in Progress -->
<div class="publications">
  <h2 class="bibliography-title">Work in progress</h2>
  {% bibliography --query @unpublished[note=Work in Progress] %}
</div>
