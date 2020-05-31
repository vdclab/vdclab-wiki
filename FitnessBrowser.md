---
title: Fitness Browser
description: Browse thousands of genome-wide fitness experiments from diverse bacteria, identify fitness phenotypes and compare fitness between genes and organisms.
published: true
date: 2020-05-31T19:36:37.110Z
tags: bacteria, comparative genomics, functional association, database, gene, fitness, browser, co-occurrence, conservation, omics, orthologs, phenotype, essentiality
---

# Fitness Browser

> The Fitness Browser was developed by the Arkin lab and displays thousands of genome-wide fitness assays from the Deutschbauer lab, the Arkin lab, and collaborators (including de Crecy lab).
>
> The fitness data is collected using randomly barcoded transposons (RB-TnSeq). Each fitness experiment is based on a pool of 30,000 to 500,000 mutant strains. Every mutant strain has a transposon inserted at a random location in the genome, and each transposon includes a random barcode that allows us to track the abundance of that strain by using PCR followed by DNA sequencing ("BarSeq"). To link the barcode to the location in the genome, we use a more complicated TnSeq-like protocol.
>
>For each fitness experiment, we compare the abundance of each strain at the end of the experiment to its abundance at the beginning. The beginning sample is also referred to as the "Time0" sample. Typically, we recover the pool of mutants from the freezer in rich media, wash the cells and take Time0 sample(s), and transfer the washed cells into many different tubes or wells. Thus, many different conditions may be compared to the same Time0 sample(s).
{.is-info}

## Ease of Use

- The website is very easy to use and the help page has detailed, easy to read descriptions of exactly what is being looked at and what that means, in regards to fitness score values. 

## User Notes  
- Gene fitness values: 
	• Fitness = 0 means the mutant grew similarly to most other mutants under those conditions and wildtype. 
	• Fitness > 0 (positive) means that the gene could be potentially harmful under those conditions, and that disrupting the gene increased the organisms fitness. 
	• Fitness < 0 (negative) means that the gene was important under those conditions and that disrupting the gene decreased the organisms fitness. 
- Gene fitness values with a |t| >/= 4 can be considered significant (or reliably different from a fitness score of 0)
- Degree of Gene fitness values:
	• -1 < Fitness < 1 indicates the loss of the gene has a subtle phenotype that may be significant (check t-score)
	• -2 < Fitness < 2 indicates that the loss of the gene has strong effects on fitness
- Cofitness represents the Pearson correlation between the fitness pattern of two genes. 
- Conserved cofitness is evidence of a functional relationship, and means that the two genes and their orthologs all have cofitness scores > 0.6.

## Website

- [Fitness Browser *Main Page*](http://fit.genomics.lbl.gov/cgi-bin/myFrontPage.cgi)
{.links-list}

## Help

- [Fitness Browser *Help Page*](http://fit.genomics.lbl.gov/cgi-bin/help.cgi)
{.links-list}

## Citation

- Price, M. N., Wetmore, K. M., Waters, R. J., Callaghan, M., Ray, J., Liu, H., ... & Carlson, H. K. (2018). [Mutant phenotypes for thousands of bacterial genes of unknown function.](https://www.nature.com/articles/s41586-018-0124-0) Nature, 557(7706), 503-509.
{.grid-list}