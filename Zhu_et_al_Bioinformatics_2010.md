---
title: ChIPpeakAnno a Bioconductor package to annotate ChIP-seq and ChIP-chip data
doi: 10.1186/1471-2105-11-237
tags: chip-seq, visualisation
author: [Saket Choudhary]
date: 2015-08-17
link: http://www.biomedcentral.com/1471-2105/11/237/
---

## Overview
Zhe et al. developed [ChIPPeakAnno](http://bioconductor.org/packages/release/bioc/html/ChIPpeakAnno.html) a Bioconductor
package to allow annotation of peaks resulting from Chip-Seq or other related experiments where the
output is a set of genomic regions. 
Features:
- View distance of peaks from nearest genes as a table/pie chart/histogram
- Determine the significance of overlap between replicates or binding sites
- Venn diagrams to visualise the distance
- Extract sequence chunks near peaks
- GO analysis of flanking genes


Similar packages:
- [CEAS](http://liulab.dfci.harvard.edu/CEAS/)
- [CisGenome](http://www.biostat.jhsph.edu/~hji/cisgenome/)

For determining the significance of overlap between replicates: Hypergeometric test


