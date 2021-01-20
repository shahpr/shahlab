---
layout: paper
title: "iteRates: An R package for implementing a parametric rate comparison on phylogenetic trees."
year: 2014
ref: Fordyce <i>et al. Evol Bioinfo</i> 2014
nickname: iterates-rpackage
journal: Evol Bioinfo
volume: 10
issue: 
pages: 127-130
authors: "Fordyce JA, Shah P, and Fitzpatrick BM."
lab: "Shah"
image: /images/papers/fordyce-iterates.png
redirect_from: 
fulltext: 
pdf: /pdfs/papers/Fordyce_Evol_Bioinform_Online_2014.pdf
pdflink: 
github: 
pmid: 25125968
pmcid: PMC4125422
f1000: 
doi: 10.4137/EBO.S16487
dryad_doi: 
altmetric_id: 
figshare: 
category: paper
published: true
embargo: false
peerreview: true
review: false
tags: chronogram diversification-rate phylogeny rate-variation phylo-method
---
# Abstract 

Patterns of diversification rate variation detected in phylogenetic hypotheses are frequently used to infer historical, ecological, and evolutionary processes. The parametric rate comparison (PRC) is a method for detecting rate variation in trees that models branch lengths as random variables drawn from familiar statistical distributions. iteRates is a library of functions for the R statistical computing environment for implementing PRC on phylogenetic trees. Here, we describe some of the functions in iteRates for subtree identification, tree manipulation, applying the PRC and <i>K</i>-clades PRC analyses, and conducting a whole-tree randomization test.

## Software

The library for parametric rate comparisons is released as an R package: [iteRates][1] with a detailed [manual][2]. To identify shifts in rates of diversification along lines of common ancestry, we iteratively compare each monophyletic subtree to the remainder tree obtained by pruning out the subtree.

[1]: https://cran.r-project.org/web/packages/iteRates/
[2]: https://cran.r-project.org/web/packages/iteRates/iteRates.pdf
