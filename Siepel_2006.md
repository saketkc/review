---
title: New methods for detecting lineage-specific selection 
doi: 
tags: 
author: [Saket Choudhary]
date: 
link: 
---


# Introudction

Older algorithms for detecting sequences under selection assume that the
selection pressures are same across all branches of a phlogeny or
focus on a specific lineage. phyloP and DLESS(Detection of Lineage-Specific Selection)

Given sequencing data, questions:

1. Are some subsequences evolving faster/slower than others


Two problems:
1. Sequnences(especially noncoding) that are considerved across species.and are likely to bu subjected to 
negative selection
2. Identifying protein-coding genes that have high dn/ds ratio
Digression:

dN : Degree by which two homologous sequences differ at non-synonymous sites(non-synonymous mutations cause an AA change)
More specfically dN is the number of non-synonymous mutations at the non-synonymous sites

$dN = \frac{\text{Number of non-synonymous mutattions}}{\text{Number of non-synonymous sites}}$

dS: Degree by which two homologous coding sequences differ with respect to synomyous mutations(mutations that do not result in AA change)

$dN = \frac{\text{Number of synonymous mutattions}}{\text{Number of synonymous sites}}$


## The Model


phastCons:

Two state HMM :
-c conserved
-n nonconserved

DLESS: Same principle but also allows for the insertions and deltions along phylogeny: 2k+2 states: conserved, nonconserved, lost or gain

