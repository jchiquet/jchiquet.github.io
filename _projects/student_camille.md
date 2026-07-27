---
layout: page
title: Camille Charbonnier
description: Inférence de réseaux de régulation génétique à partir de données du transcriptome non indépendamment et indentiquement distribuées (2009-2012)
img: /assets/img/camille_charbonnier.jpg
importance: 3
category: 'PhD student (alumni)'
---

Camille's PhD was co-supervised with [Christophe Ambroise]()
(50%/50%), from 2009 to 2012.

### Summary

This thesis develops statistical methods for inferring gene regulatory networks from transcriptomic data that violate the classical independent and identically distributed (iid) sampling assumption, in particular time-course and structured experimental designs. It proposes weighted-Lasso and cooperative-Lasso penalized estimators of Gaussian graphical models that incorporate prior structural information (temporal ordering, replicate structure) to improve network recovery, together with model selection procedures adapted to these dependent settings. The resulting methods are implemented in the SIMoNe R package and applied to real transcriptomic time-course data.

### PhD manucript

<div class="publications">

{% bibliography -f student_theses -q @*[author ~= Charbonnier]* %}

</div>

### Journal papers

<div class="publications">

{% bibliography -f chiquet_preprint -q @*[author ~= Charbonnier]* %}

{% bibliography -f chiquet_journal -q @*[author ~= Charbonnier]* %}

{% bibliography -f chiquet_inbook -q @*[author ~= Charbonnier]* %}

</div>


### Conferences

<div class="publications">

{% bibliography -f chiquet_inter_contr_talks -q @*[author ~= Charbonnier]* %}

{% bibliography -f chiquet_nat_contr_talks -q @*[author ~= Charbonnier]* %}

</div>
