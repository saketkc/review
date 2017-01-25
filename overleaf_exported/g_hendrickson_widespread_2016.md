**Goal:** Are RNA-RBP interaction specific to the RBP context or is there a general mechanism governing these interactions leading to a certain chromatin state.

RBPS bind nascent RNAs to dictate splicing, stability, localization and translation. Many DNA binding proteins can bind to RNA to modulate transcriptional and post-transcriptional states.

RNAs play a key role in chromatin state. A large class of long noncoding RNAs (lncRNAs) play a role in binding and modulating activity of chromatin modifying proteins. Example includes lncRNA Xist whihc recruits various transcriptional and epigenetic repressors.

*The whole motivation of this paper is to better characterise where and when specific chromatin markers take action and if lncRNAs are the best way to explain them.*

A key example of RNA interaction with proteins playing role in silencing is of PRC2 which binds transcripts with high affinity but with low specificity. Earlier models predicted lncRNA role in guiding PRC2 to specific loci but was recised to reflect PRC2 actually sensing the RNA context to modulate its activity.

**Assay**: fRIP-seq of 24 proteins in K562. fRIP= formaldehyde cross linking RNA immunoprecipitation.

fRIP-Seq
========

: CLIP methods are(were) expensive and required lot of input RNA material, scale poorly across multiple antibodies. Chromatin associated proteins or CAPs lack the traditional RNA binding domains(RBD)

Using more formaldehyde resulted in lower protein and RNA recovery. Higher formaldehyde leads to ’over crosslinking’ which results in protein-nucleciacid macro-aggregates that can either be lost to the soluble fraction or are too large for effective capture.

Formaldehyde treatment is follwed by sonication and incubation with a targeted antibody. One of the advantages of this over the RIP-seq was that formadehyde treatment prvents post lysis mixup of RNA-protein complexes.

One observation was that the binding signature of each protein was unique: they had enrichment and under-representation for a unique set of transcripts. This unique pattern was confirmed not to be related to the amount of input RNA nor to the status of protein identified as RNA or DNA binding.

**Question** I have had a hard time grpoking the physical menaning of $\\log(\\frac{fRIP}{input})$ The input term refers to the RNA-Seq counts(presumably) of the whole lysate. Numerator term refers to the counts of protein associated RNA.

Scenario:

1.  binding non specific: RBP will bind everywhere
