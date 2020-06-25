---
title: InterEvDock2
description: A docking server to predict the structure of protein-protein interactions using evolutionary information.
published: true
date: 2020-06-25T17:14:10.083Z
tags: tool, proteins, prediction, interaction, protein-protein
editor: markdown
---

# InterEvDock2

> InterEvDock2 is a server for protein docking running the InterEvScore potential specifically designed to integrate evolutionary information in the docking process. The InterEvScore potential was developed for heteromeric protein interfaces and combines a residue-based multi-body statistical potential with evolutionary information derived from the multiple sequence alignments of each partner in the complex. In the InterEvDock2 server, the systematic docking search is performed using the FRODOCK2 program and the resulting models are re-scored with InterEvScore together with the SOAP_PP atom-based statistical potential found to increase the confidence of the predictions.
&NewLine;
InterEvDock2 is an update of InterEvDock that can handle protein sequences as inputs, and not only protein 3D structures. When a sequence is provided by the user, a comparative modeling step based on an automatic template search protocol builds models for the individual protein partners, prior to docking. In InterEvDock2, in case the user has biological input such as a position that is known to be involved in the interface between the two protein partners, constraints can be specified for use in the docking procedure. This can be crucial to ensure that all available biologically relevant information is used for InterEvDock2 predictions. In addition, InterEvDock2 implements the possibility to submit structures of oligomers as input to the free docking. Such an option is generally complicated in co-evolution analyses since the joint MSAs have to be generated for every chain of an oligomer. This process is now fully automatized in InterEvDock2.
{.is-info}



## Website

- [InterEvDock2 *Main Page*](https://bioserv.rpbs.univ-paris-diderot.fr/services/InterEvDock2/)
{.links-list}

## User Notes
- (!) Some jobs may take up to or more than 24 hours to complete so it is essential to plan ahead when using this tool in the anticipation of any deadlines
- Jobs/data/tools are most easily utilized, managed through a registered user account

## Citations

- Quignot C, Rey J, Yu J, Tufféry P, Guerois R, Andreani J. [InterEvDock2: an expanded server for protein docking using evolutionary and biological information from homology models and multimeric inputs.](https://academic.oup.com/nar/article/46/W1/W408/4993789) Nucleic Acids Res. 2018 Jul 2;46(W1):W408-16.
- Yu J, Vavrusa M, Andreani J, Rey J, Tufféry P, Guerois R. [InterEvDock: A docking server to predict the structure of protein-protein interactions using evolutionary information.](https://academic.oup.com/nar/article/44/W1/W542/2499337) Nucleic Acids Res. 2016 Jul 8;44(W1):W542-9.
-	Andreani J, Faure G, Guerois R. [InterEvScore: a novel coarse-grained interface scoring function using a multi-body statistical potential coupled to evolution.](https://academic.oup.com/bioinformatics/article/29/14/1742/229148) Bioinformatics. 2013 29(14):1742-9.
{.grid-list}