---
title: PaperBLAST
description: Curated BLAST allowing the retrieval of published data starting from BLAST of a protein sequence
published: true
date: 2023-12-16T19:53:52.902Z
tags: reference, annotation, tool, sequence analysis, proteins, sequence similarity, specialized search, data capture, homolog discovery, literature
editor: markdown
dateCreated: 2020-04-02T00:28:36.724Z
---

# PaperBLAST

> PaperBLAST builds a database of protein sequences that are linked to scientific articles. These links come from automated text searches against the articles in EuropePMC and from manually-curated information from GeneRIF, UniProtKB/Swiss-Prot, BRENDA, CAZy (as made available by dbCAN), CharProtDB, MetaCyc, EcoCyc, REBASE, and the Fitness Browser. Given this database and a protein sequence query, PaperBLAST uses protein-protein BLAST to find similar sequences with E < 0.001. 
{.is-info}

## Website

- [PaperBLAST *Main page*](http://papers.genomics.lbl.gov/cgi-bin/litSearch.cgi)
{.links-list}


## Notes from users 

This should be the first step to be done when working a new gene. It allows to extract papers on several members of a protein family. It is important however to check the links manually. Searches also will miss some references that are not open access and have not mentioned the protein Locus_tag in the abstract/title.  

## Ease of use 

No specific help, but very easy to use and self-explanatory. The search using [family ids](https://papers.genomics.lbl.gov/cgi-bin/hmmSearch.cgi) not sequence is not totally intutive to find.


## Citation

- Price MN, Arkin AP, [PaperBLAST: Text Mining Papers for Information about Homologs](https://msystems.asm.org/content/2/4/e00039-17). mSystems 2017, 2(4):e00039-00017.
{.grid-list}