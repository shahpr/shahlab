---
layout: paper
title: A parametric method for assessing diversification-rate variation in phylogenetic trees.
year: 2013
ref: Shah <i>et al. Evolution</i> 2013
nickname: iterates-model
journal: Evolution
volume: 67
issue: 2
pages: 368-377
authors: Shah P, Fitzpatrick BM, and Fordyce JA.
lab: "Shah"
image: /images/papers/shah-iterates.png
redirect_from: 
fulltext: 
pdf: /pdfs/papers/Shah_Evolution_2013.pdf
pdflink: 
github: 
pmid: 23356610
pmcid: 
f1000: 
doi: 10.1111/j.1558-5646.2012.01791.x
dryad_doi: 
altmetric_id: 
figshare: 
category: paper
published: true
embargo: false
peerreview: true
review: false
tags: Adaptive radiation chronogram diversification rate phylogeny Plethodon phylo-method
---
# Abstract 

Phylogenetic hypotheses are frequently used to examine variation in rates of diversification across the history of a group. Patterns of diversification-rate variation can be used to infer underlying ecological and evolutionary processes responsible for patterns of cladogenesis. Most existing methods examine rate variation through time. Methods for examining differences in diversification among groups are more limited. Here, we present a new method, parametric rate comparison (PRC), that explicitly compares diversification rates among lineages in a tree using a variety of standard statistical distributions. PRC can identify subclades of the tree where diversification rates are at variance with the remainder of the tree. A randomization test can be used to evaluate how often such variance would appear by chance alone. The method also allows for comparison of diversification rate among a priori defined groups. Further, the application of the PRC method is not restricted to monophyletic groups. We examined the performance of PRC using simulated data, which showed that PRC has acceptable false-positive rates and statistical power to detect rate variation. We apply the PRC method to the well-studied radiation of North American <i>Plethodon</i> salamanders, and support the inference that the large-bodied <i>Plethodon glutinosus</i> clade has a higher historical rate of diversification compared to other <i>Plethodon</i> salamanders.

## Software

The library for parametric rate comparisons is released as an R package: [iteRates][1] with a detailed [manual][2]. To identify shifts in rates of diversification along lines of common ancestry, we iteratively compare each monophyletic subtree to the remainder tree obtained by pruning out the subtree.

[1]: https://cran.r-project.org/web/packages/iteRates/
[2]: https://cran.r-project.org/web/packages/iteRates/iteRates.pdf
