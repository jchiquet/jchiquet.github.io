---
layout: page
title: Bastien Batardière
description: Apprentissage statistique pour l'analyse multivariée de données de comptage de grande dimension  (2021-2024, 50%)
img: /assets/img/bastien_batardiere.jpg
importance: 2
category: 'PhD student (alumni)'
---

Bastien's PhD is supported by the [ANR SingleStatOmics grant](https://anr-singlestatomics.pages.math.cnrs.fr/). IT is co-supervized with [Joon Kwon](https://joon-kwon.github.io/).

### Summary

This thesis develops statistical and computational tools for the analysis of high-dimensional multivariate count data, within the framework of the Poisson Log-Normal (PLN) model and its variational inference. It introduces a Zero-Inflated PLN (ZIPLN) extension to account for excess zeros frequently observed in real count data (e.g., microbiome or single-cell data), an adaptive optimization method (AdaLVR) that improves the scalability of variational inference to datasets with several thousand variables, and corrected variational estimators for quantifying parameter uncertainty. The resulting methods are implemented in the PLNmodels and pyPLNmodels R/Python packages and applied to genomic, ecological, and microbiome count datasets.

### PhD manucript

<div class="publications">

{% bibliography -f student_theses -q @*[author ~= Batardière]* %}

</div>

### Journal papers

<div class="publications">

{% bibliography -f chiquet_preprint -q @*[author ~= Batardière]* %}

{% bibliography -f chiquet_journal -q @*[author ~= Batardière]* %}

</div>


### Conferences

<div class="publications">

{% bibliography -f chiquet_inter_contr_talks -q @*[author ~= Batardière]* %}

{% bibliography -f chiquet_nat_contr_talks -q @*[author ~= Batardière]* %}

</div>
