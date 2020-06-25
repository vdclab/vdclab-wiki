---
title: DISPLAR
description: DISPLAR is a neural network method. Given the structure of a protein known to bind DNA, the method predicts residues that contact DNA.
published: true
date: 2020-06-25T16:11:29.021Z
tags: tool, proteins, dna, prediction, binding
editor: markdown
---

# DISPLAR

> DISPLAR is a neural network method. Given the structure of a protein known to bind DNA, the method predicts residues that contact DNA. The inputs to the neural network include position-specific sequence profiles and solvent accessibilities of each residue and its spatial neighbors. The neural network is trained on known structures of protein-DNA complexes. On our test set, DISPLAR shows prediction accuracy over 80% and coverage of over 60% of actual DNA-contacting residues.
{.is-info}



## Website

- [DISPLAR *Main Page*](https://pipe.rcc.fsu.edu/displar.html)
{.links-list}

## User Notes
- Make take time for processing of request; it is best to perform these kinds of queries (prediction, modeling webservers) in advance of when their results are needed; prepare for any cases of server outages, backlogged queues, etc.
- Provides output via email in a plain text format: predicted likelihood of DNA binding per residue of a provided PDB structure (file or copy-pasted into text box of submission page)

## Citation

- Tjong , H. and Zhou, H.-X. [DISPLAR: an accurate method for predicting DNA-binding sites on protein surfaces.](http://nar.oxfordjournals.org/cgi/content/abstract/35/5/1465) Nucl. Acids Res. 35:1465-1477 (2007)
{.grid-list}