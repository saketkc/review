---
title: Model-based Analysis of ChIP-Seq (MACS)
doi: 10.1186/gb-2008-9-9-r137
tags: chip-seq, methods
author: [Saket Choudhary]
date: 2015-08-17
link: http://www.genomebiology.com/content/9/9/R137
---


## Overview
MACS is a peak caller focused at ChIP-Seq data.
It models the shift of ChIP-Seq tags and uses it to 
improve the spatial resolution of predicted binding sites
Uses dynamic poisson


## Intro

### Biology I didn't know about:
Cistrome: Cistr(Cistron)+ome(genome)
Cis Regulatory Elements: Regions of non-coding DNA which regulate transcription of genes 'nearby'.
In principle the CRES will be located in the gene or very close to the gene they are regulating.
Example: Promoters: ~40 bp sequences located upstream of the TSS.. Consists of the site
where transcription is initiated, TATA box, TFIIB recognition site, initiator and downstream core
promoter element. The TFs bind to promoter region to initiate transcription. This is further
regulated by the presence of encahcers either upstream, downstream, within introns or far away from
the gene they regulate. Important: CREs do not code for RNA/protein in lieu of their presence in
the non coding region.

Example of a cis-acting regulatory element is the lac operon: The lac operator itself does not code for RNA/proteins
but is bound by the lac repressor which prevents the transcription of nearby genes
Cis-regulatory elemts are thus often sites of TF binding,

Trans Elements: These will often consist of sequences containing a gene that will be used in the regulation
of another target gene. The trans acting gene can be on the same chromosome but the tran activity
happens through the intermediate protein/RNA that it encodes. So Trans elements code for RNA/protein
which are also said to act in trans to the gene they are targeting.


Coming back to cistrome: Cistron is essentially.

Another digression on polycistronic/monocistronic: A cistron is a gene
Very helpful and trustworthy answer here: http://biology.stackexchange.com/a/19186/6615

Cis-trans test: Wild type T4 can form plaques in Ecoli B and K12. Mutations in rII region cause a
plaque in EColiB but not in K12. Complementation tests were performed: Mix phage with two different
mutations. complementation occurs only if two mutations are in different genes. Essentially when
two different strains with different HOMOZYGOUS recessive mutation exhibitinh the same phenotype
produce offspring with the wild-type phenotype, then a complementation has occured and this can
occur only if the mutations are in two different genes. Basically each strain's genome
will supply the wild type for a corresponding mutated site and the the mutation being recessive,
will result in a wild-type phenotype.

Using the word 'cistron' just makes us aware of gene's behaviour in a complementation test.

So a Cistrome: Collection of cis-acting targets of  a trans-acting factor on a genom wide scale.
Basically, the invivo genome wide locations of TF binding and histone modificatio. 

Trans acting factors control gene expression: Transcription Initiation Complex 
is composed of promoters+DNA binding proteins=> cis acting elements(promoters) + trans-
acting factors(DNA binding proteins)

Trans acting factors properties:
- Subunits of RNA polymerase
- bind to RNA pol to stabilise initiation complex
- bind to promoters at specific sequences
-

Each TF has two domains: One binds to DNA
and the second one required for DNA activation

----End Digression-----



