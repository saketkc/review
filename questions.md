1. Predict TSS using conservation data?
i
GERP: identifies sites that show few substitutions than would be expected from neutral 
substution. Then extends these fragments  to define sequences that are 
under evolutinray constrainti: 33 mamalian genomes

RS score = # of susbstitions expected under neutral substituion- observed
Higher rate implies selective constraint and negative implies ubstittuion surplus


phyloP: HMM based approach models the quantity and distribution of the constraint within alignment
Start with an MSA of homologos sequences, model their 

phastcons and GeRP will mostly agree to 90% sites. At sites which might be under weak constraint and
are between two sites under strong constraint and still selects it 
because it might be part of one big constraint

phylop does not take into account the conservation at neighboring sites and so if you go to UCSC 
you will observe it has a less smooth experience 

Phylop depends only on the assumption of neutral evolution like GERP++ whears phastcons
also takes into account negative selection

