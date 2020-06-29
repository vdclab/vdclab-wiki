---
title: Two Sample Logos
description: wo Sample Logo is a web-based application that calculates and visualizes differences between two sets of aligned samples of amino acids or nucleotides.
published: true
date: 2020-06-29T14:20:14.678Z
tags: tool, sequence alignment, gene, data visualization, protein
editor: markdown
---

# Two Sample Logos

> Two Sample Logo is a web-based application that calculates and visualizes differences between two sets of aligned samples of amino acids or nucleotides. Statistical significance is calculated for each residue at each position in the aligned groups of sequences, where the null hypothesis is that the residue is generated according to the same distribution in both positive and negative samples. Two Sample Logos can be used to determine statistically significant residues around various active sites, protein modification sites, or to find differences between two groups of sequences that share the same sequence motif.
&NewLine;
The software supports two types of graphical representation: (i) statistically significant residues are plotted using the same size for each residue symbol, (ii) statistically significant symbols are plotted using the size of the symbol that is proportional to the difference between the two samples. Residues are separated in two groups: (i) enriched in the positive sample, and (ii) depleted in the positive sample. In all types of representations, symbols can be plotted using various color schemes and shared residues can be added to the plot in order to visualize the motif itself. The p-value is calculated using the binomial distribution (more accurate, but slower option) or the t-test (less accurate, but significantly faster).
{.is-info}



## Website

- [Two Sample Logos *Create TSL Page*](http://www.twosamplelogo.org/cgi-bin/tsl/tsl.cgi)
{.links-list}

## User Notes

- order of input (positive, negative sequences) matters, influences output
- lengths of inputs between positive and negative sequences must be of the same lengths

## Citation

- Vacic V., Iakoucheva L.M., and Radivojac P. ["Two Sample Logo: A Graphical Representation of the Differences between Two Sets of Sequence Alignments."](https://academic.oup.com/bioinformatics/article/22/12/1536/207720) Bioinformatics, 22(12): 1536-1537. (2006) 
{.grid-list}