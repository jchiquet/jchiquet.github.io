---
layout: page
title: François Victor
description: 'Développement de méthodes d’apprentissage statistique et d’apprentissage par transfert pour la caractérisation du potentiel agro-écologique et le screening des ressources génétiques (2024-xx, 25%)'
img: /assets/img/francois_victor.jpg
importance: 2
category: 'PhD student (current)'
---

François' thesis focuses on the development of hybrid statistical and deep learning models for domain transfer in plant genetics. It is financed by the CoBreeding project of the PEPR Agroécologie-Numérique and co-supervised with [Tristan Mary-Huard](https://moulon.inrae.fr/en/personnes/tmaryhuard/), [Jean-Benoist Léger](https://www.hds.utc.fr/~legerjea/) adn [Alain Charcosset](https://moulon.inrae.fr/personnes/acharcosset/).

### Summary

François's PhD develops statistical and deep learning methods to predict the performance of maize hybrids that can be formed from pools of parental lines, as part of the CoBreeding project (PEPR Agroécologie Numérique). Because only a small, unbalanced fraction of possible hybrid combinations is ever observed in the field, the work combines state-of-the-art mixed models from quantitative genetics with neural network architectures (variational autoencoders) to scale inference to large genomic and phenotypic datasets while preserving interpretability. The thesis addresses three complementary questions: predicting the stability of a hybrid's performance across environments from a generalized mixed model with genotype-dependent residual variance, predicting hybrid performance directly in target environments by reformulating factor-analytic and AMMI genotype-by-environment models in a variational framework, and transferring information learned from a data-rich reference population (US maize lines, from the Genomes To Fields initiative) to a more limited population of European lines through transfer learning and domain adaptation.

### PhD manucript

<div class="publications">

{% bibliography -f student_theses -q @*[author ~= Victor]* %}

</div>

### Journal papers

<div class="publications">

{% bibliography -f chiquet_preprint -q @*[author ~= Victor]* %}

{% bibliography -f chiquet_journal -q @*[author ~= Victor]* %}

</div>


### Conferences

<div class="publications">

{% bibliography -f chiquet_inter_contr_talks -q @*[author ~= Victor]* %}

{% bibliography -f chiquet_nat_contr_talks -q @*[author ~= Victor]* %}

</div>
