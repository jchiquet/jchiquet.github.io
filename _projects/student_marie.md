---
layout: page
title: Marie Perrot-Dockes
description: 'Regularization tools for multivariate analysis: application to multi-omics (2016-2019)'
img: /assets/img/marie_perrot-dockes.png
importance: 2
category: 'PhD student (alumni)'
---

Marie's PhD was co-supervised with [Céline
Lévy-Leduc](https://www6.inra.fr/mia-paris/Equipes/Membres/Celine-Levy-Leduc)
(50%/50%) and Laure Sansonnet, from 2016 to 2019.

### Summary

This thesis develops regularized methods for variable selection in high-dimensional multivariate linear models, where the response is a vector of correlated outcomes rather than a single variable. It proposes procedures that jointly estimate the regression coefficients and the covariance structure of the residuals, improving selection accuracy when responses are strongly dependent, and establishes theoretical guarantees for the resulting estimators. The methodology is implemented in the MultiVarSel R package and applied to metabolomics data (LC-MS), where it is used to identify which molecular features are jointly associated with experimental conditions while accounting for the complex correlation structure between metabolites.

### PhD manucript

<div class="publications">

{% bibliography -f student_theses -q @*[author ~= Perrot]* %}

</div>

### Journal papers

<div class="publications">

{% bibliography -f chiquet_preprint -q @*[author ~= Perrot]* %}

{% bibliography -f chiquet_journal -q @*[author ~= Perrot]* %}

</div>


### Conferences

<div class="publications">

{% bibliography -f chiquet_inter_contr_talks -q @*[author ~= Perrot]* %}

{% bibliography -f chiquet_nat_contr_talks -q @*[author ~= Perrot]* %}

</div>
