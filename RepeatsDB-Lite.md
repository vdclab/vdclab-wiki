---
title: RepeatsDB Lite
description: RepeatsDB-lite is a web server for the prediction of repetitive structural elements and units in tandem repeat (TR) proteins.
published: true
date: 2020-07-16T16:06:01.545Z
tags: tool, proteins, prediction
editor: markdown
---

# RepeatsDB Lite

> RepeatsDB-lite is a web server for the prediction of repetitive structural elements and units in tandem repeat (TR) proteins. The tool takes as input a PDB structure from a file or ID and predicts if the protein contains a repeat region or not, the position of each repeat unit and the classification of the repeat (class, subclass and, if possible, type or fold).
>
> RepeatsDB-lite input is a file or ID. In case of ID input, RepeatsDB lite downloads the structure from PDB services. The prediction is separate for each chain of the PDB. The user can optionally select a specific chain or run the predictor in the "all chain" mode, that runs the prediction for each chain in the structure. By default, the prediction on the first chain of the PDB file is calculated.
>
> RepeatsDB-lite output shows, by chain, the prediction of repeat regions. It includes several output files for download and sequence and structure viewers to support data visualization.
{.is-info}

 

## Website 

- [RepeatsDB Lite *Main Page*](http://protein.bio.unipd.it/repeatsdb-lite/)
 {.links-list}
 
 ## Notes from the user
 - Useful for proteins with repeated domains
 - Structural alignment recolors each subunit and makes it easy to see small differences
 - Classifies each domain and gives links to other proteins with similar domains.
 
 ## Ease of use
 > This tool is easy to use, simply input a protein databank ID and a chain to analyze. There is a 3d structural alignment and a sequence alignment heatmap that give the user different options for viewing their query.

## Citation 

- Hirsh, L., Paladin, L., Piovesan, D., & Tosatto, S. C. E. (2018). RepeatsDB-lite: a web server for unit annotation of tandem repeat proteins. Nucleic acids research, 46(W1), W402-W407.
{.grid-list}