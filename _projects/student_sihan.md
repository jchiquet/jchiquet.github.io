---
layout: page
title: Sihan Xie
description: 'DeepSelectGene: Apprentissage profond à partir de données de génotypes
  et application à la sélection génomique (2023-xx, 25%)'
img: /assets/img/sihan_xie.png
importance: 2
category: 'PhD student (current)'
---

Sihan's thesis focuses on deep learning generative models applied to genotyping data in animal genetics. His thesis supervisor is [Eric Barrey](https://gabi.jouy.hub.inrae.fr/presentation/annuaire-des-pages-professionnelles/barrey-eric), at INRAE's Animal Genetics department, and the thesis is co-supervised by [Blaise Hanczar and myself](https://sites.google.com/site/bhanczarhomepage/). It is financed 100% by INRAE via the DIGIT-BIO metaprogramme.

### Summary

Deep learning models are increasingly used to predict phenotypes from genotypes, for human diseases as well as production traits in genomic selection, but training them requires many genotype-phenotype pairs -- rarely available for species genotyped on only a few thousand animals. Sihan's PhD works around this limit by chaining two deep learning models: a first, generative model (e.g. generative adversarial networks) trained on scarce but representative real data to simulate additional, realistic genotype data (50--800K SNPs); this augmented dataset then trains a second, simpler model dedicated to phenotype prediction, building on exploratory work from the GenIALearn project on bovine genomic selection (Metaprogramme DIGIT-BIO, 2022--2024). His first paper compared several generative models (VAEs, diffusion models, GANs) for simulating discrete genotype data, unconditioned or phenotype-conditioned, showing they capture genetic patterns and preserve genotype-phenotype associations -- opening the way to privacy-preserving data sharing and to this augmentation strategy for phenotype prediction from only a few thousand genotype-phenotype pairs.

### PhD manucript

<div class="publications">

{% bibliography -f student_theses -q @*[author ~= Xie]* %}

</div>

### Journal papers

<div class="publications">

{% bibliography -f chiquet_preprint -q @*[author ~= Xie]* %}

{% bibliography -f chiquet_journal -q @*[author ~= Xie]* %}

</div>


### Conferences

<div class="publications">

{% bibliography -f chiquet_inter_contr_talks -q @*[author ~= Xie]* %}

{% bibliography -f chiquet_nat_contr_talks -q @*[author ~= Xie]* %}

</div>
