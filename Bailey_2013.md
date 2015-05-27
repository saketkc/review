---
title: Practical Guidelines for the Comprehensive Analysis of ChIP-seq Data
doi: 10.1371/journal.pcbi.1003326
tags: chip-seq, best-practices
author: [Saket Choudhary]
date: 2015-05-27
---

Chip-Seq
- Identifying sites for protein binding
- Could be transcription factors, DNA-binding enzymes, chaperones, nucleosomes, histones
- Crosslink bound protein to DNA => Fragment Chromatin => Capture bound protein
using antibody => Sequence the ends of captured fragments
- DNA around bound sites is sheraed more easily than if not bound. The peak callers rely on
footprinting DNA around these positions
- For hinstone modification such as dna methylation and chromatin remoddelling, the peaksare genereally more spread.
This pattern of enrichment is described as “domains” because there are no peak summits.


## Sequencing Depth

- 20 million reads sufficient for mammalian TFs and chromatin modification
like histone marks since they are localized 
    - Are localized at specific narrow sites and have binding sites
    in order of thousands
    - Proteins with more binding sites or broader binding sites require more
    reads
- Control samples should be sequenced deeper to ensure sufficient coverage
of that part of genome where the actual binding happens

- _Saturation Analysis_: If the coverage depth was adequate, the peak 
calls should be consistent by increasing number of reads chosen randomly 
from the actual reads. This can be ensured making use of library complexity

- _PBC_ PCR bottle neck coefficien = Fraction of genomic locations with  exactly
one unique read to the locations covered by atleast one unique read


## Reproducibility

- Reproducibility can be measured by computing pearson correlation coefficient 
of the mapped read counts at each genomic position
- Apply an IDR cutoff to ensure peaks are reproducile across experiments.
- To reflect reproducibility of less ensriched regions, the high enriched regions need
to be thrown away before comparing PCC(I don’t know how to identify highly enriched regions)

## Motify analysis

- Motif: Sequence pattern that occurs repeatedly in a group of related proteins or DNA.
Genereally represented as a PWM that describe the probability of each possible letter at
each position in the pattern. Individual motifs generally do not contain gaps[Varible length are thus split]

- If the motif of the binding protein is already known,
doing a motif anlysis is a confirmation of that fact

- Compare discovered motifs with known motifs




