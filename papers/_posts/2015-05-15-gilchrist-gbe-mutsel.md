---
layout: paper
title: "Estimating gene expression and codon specific translational efficiencies, mutation biases, and selection coefficients from genomic data alone."
year: "2015"
ref: "Gilchrist <i>et al. Genome Biol Evol</i> 2015"
nickname: estimate-mutsel-wophi
journal: "Genome Biol Evol"
volume: 7
issue: 6
pages: 1559-1579
authors: "Gilchrist MA, Chen WC, Shah P, Landerer C, and Zaretzki R."
image: /images/papers/gilchrist-treff.png
redirect_from: 
fulltext: 
pdf: /pdfs/papers/Gilchrist_GBE_2015.pdf
pdflink: 
github: 
pmid: 25977456
pmcid: PMC4494061
f1000: 
doi: 10.1093/gbe/evv087
dryad_doi: 
altmetric_id: 
figshare: 
category: paper
published: true
embargo: false
peerreview: true
review: false
tags: CUB translation efficiency mutation bias popgen selection coefficient
---
# Abstract 

Extracting biologically meaningful information from the continuing flood of genomic data is a major challenge in the life sciences. Codon usage bias (CUB) is a general feature of most genomes and is thought to reflect the effects of both natural selection for efficient translation and mutation bias. Here we present a mechanistically interpretable, Bayesian model (ribosome overhead costs Stochastic Evolutionary Model of Protein Production Rate [ROC SEMPPR]) to extract meaningful information from patterns of CUB within a genome. ROC SEMPPR is grounded in population genetics and allows us to separate the contributions of mutational biases and natural selection against translational inefficiency on a gene-by-gene and codon-by-codon basis. Until now, the primary disadvantage of similar approaches was the need for genome scale measurements of gene expression. Here, we demonstrate that it is possible to both extract accurate estimates of codon-specific mutation biases and translational efficiencies while simultaneously generating accurate estimates of gene expression, rather than requiring such information. We demonstrate the utility of ROC SEMPPR using the <i>Saccharomyces cerevisiae</i> S288c genome. When we compare our model fits with previous approaches we observe an exceptionally high agreement between estimates of both codon-specific parameters and gene expression levels ({% eqinline \rho>0.99 %} in all cases). We also observe strong agreement between our parameter estimates and those derived from alternative data sets. For example, our estimates of mutation bias and those from mutational accumulation experiments are highly correlated ({% eqinline \rho=0.95 %}). Our estimates of codon-specific translational inefficiencies and tRNA copy number-based estimates of ribosome pausing time ({% eqinline \rho=0.64 %}), and mRNA and ribosome profiling footprint-based estimates of gene expression ({% eqinline \rho=0.53-0.74 %}) are also highly correlated, thus supporting the hypothesis that selection against translational inefficiency is an important force driving the evolution of CUB. Surprisingly, we find that for particular amino acids, codon usage in highly expressed genes can still be largely driven by mutation bias and that failing to take mutation bias into account can lead to the misidentification of an amino acid's "optimal" codon. In conclusion, our method demonstrates that an enormous amount of biologically important information is encoded within genome scale patterns of codon usage, accessing this information does not require gene expression measurements, but instead carefully formulated biologically interpretable models.