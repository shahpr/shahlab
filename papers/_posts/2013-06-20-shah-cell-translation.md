---
layout: paper
title: "Rate-limiting steps in yeast protein translation."
year: "2013"
ref: "Shah <i>et al. Cell</i> 2013"
nickname: whole-cell-translation
journal: "Cell"
volume: 153
issue: 7
pages: 1589-1601
authors: "Shah P, Ding Y, Niemczyk M, Kudla G, and Plotkin JB."
lab: "Shah"
image: /images/papers/shah-smopt.png
redirect_from: 
fulltext: 
pdf: /pdfs/papers/Shah_Cell_2013.pdf
pdflink: 
github: https://github.com/shahpr/SMoPT
github_n: SMoPT
pmid: 23791185
pmcid: PMC3694300
f1000: 
doi: 10.1016/j.cell.2013.05.049
dryad_doi: 
altmetric_id: 
figshare: 
category: paper
published: true
embargo: false
peerreview: true
review: false
tags: initiation rates ribosome density ramp SMoPT translation
---
# Abstract 

Deep sequencing now provides detailed snapshots of ribosome occupancy on mRNAs. We leverage these data to parameterize a computational model of translation, keeping track of every ribosome, tRNA, and mRNA molecule in a yeast cell. We determine the parameter regimes in which fast initiation or high codon bias in a transgene increases protein yield and infer the initiation rates of endogenous <i>Saccharomyces cerevisiae</i> genes, which vary by several orders of magnitude and correlate with 5′ mRNA folding energies. Our model recapitulates the previously reported 5′-to-3′ ramp of decreasing ribosome densities, although our analysis shows that this ramp is caused by rapid initiation of short genes rather than slow codons at the start of transcripts. We conclude that protein production in healthy yeast cells is typically limited by the availability of free ribosomes, whereas protein production under periods of stress can sometimes be rescued by reducing initiation or elongation rates.

## Stochastic Model of Protein Translation

The associated code to simulate whole-cell model of protein translation is available on [GitHub][2]. The model keeps track of all ribosomes, tRNAs and mRNAs in a cell in continuous time. The rates of initiation and elongation in the model are based on physical parameters that have been determined experimentally in yeast. 

The pacakge contains the source code, pre-compiled binaries, utility scripts and example input and output files. The source code is licensed under GNU GPLv3 license.

## Commentary

Here's the associated commentary on our paper that was featured on [Penn News][1].

[1]: http://www.upenn.edu/pennnews/news/penn-biologists-create-computer-simulation-cell-action
[2]: https://github.com/shahpr/SMoPT
