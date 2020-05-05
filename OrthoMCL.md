---
title: OrthoMCL
description: OrthoMCL is a genome-scale algorithm for grouping orthologous protein sequences.
published: true
date: 2020-05-05T17:46:49.700Z
tags: proteins, video, database, 2011, 2007, orthologs, 2003, 2006, eukaryota
---

# OrthoMCL

> OrthoMCL is a genome-scale algorithm for grouping orthologous protein sequences. It provides not only groups shared by two or more species/genomes, but also groups representing species-specific gene expansion families. So it serves as an important utility for automated eukaryotic genome annotation. OrthoMCL starts with reciprocal best hits within each genome as potential in-paralog/recent paralog pairs and reciprocal best hits across any two genomes as potential ortholog pairs. Related proteins are interlinked in a similarity graph. Then MCL (Markov Clustering algorithm,Van Dongen 2000; www.micans.org/mcl) is invoked to split mega-clusters. This process is analogous to the manual review in COG construction. MCL clustering is based on weights between each pair of proteins, so to correct for differences in evolutionary distance the weights are normalized before running MCL.
&NewLine;
OrthoMCL is similar to the INPARANOID algorithm (Remm, Storm et al. 2001), but is extended to cluster orthologs from multiple species. OrthoMCL clusters are coherent with groups identified by EGO (Lee, Sultana et al. 2002), and an analysis using EC number suggests a high degree of reliability (Li, Stoeckert et al. 2003).
&NewLine;
In a recent assessment (Chen, et al. 2007), the performance of seven widely used orthology detection algorithms, representing three kinds of strategies (phylogeny-based, evolutionary distance-based and BLAST-based), are evaluated using the statistical technique Latent Class Analysis (LCA). LCA is useful when there are large data sets available but no gold standard. The results show an overall trade-off between sensitivity and specificity among these algorithms, with INPARANOID and OrthoMCL as the two best methods having both False Positive (FP) and False Negative (FN) error rates lower than 20%. 
{.is-info}

## Website

- [OrthoMCL *Main Page*](https://orthomcl.org/orthomcl/)
- [videos *tutorials*](https://orthomcl.org/orthomcl/showXmlDataContent.do?name=XmlQuestions.Tutorials)
{.links-list}
## Notes from Users 
Many tools to explore groups of orthologs, you can also input your own sequences to assign them to groups. Workshop are available every year to learn the tool. This tool/database only regroup cluster of orthologs for Eukaryotes.

## Ease of use
This web site requires exploration and watching the videos to master it plainly. Careful that it is only a ressource for Eukaryotes.

## Citations

- Li Li, Christian J. Stoeckert, Jr., and David S. Roos [OrthoMCL: Identification of Ortholog Groups for Eukaryotic Genomes](https://genome.cshlp.org/content/13/9/2178.full) Genome Res. 2003 13: 2178-2189.
-	Feng Chen, Aaron J. Mackey, Christian J. Stoeckert, Jr., and David S. Roos [OrthoMCL-DB: querying a comprehensive multi-species collection of ortholog groups](https://academic.oup.com/nar/article/34/suppl_1/D363/1133676) Nucleic Acids Res. 2006 34: D363-8.
- Feng Chen, Aaron J. Mackey, Jeroen K. Vermunt, and David S. Roos [Assessing Performance of Orthology Detection Strategies Applied to Eukaryotic Genomes](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0000383) PLoS ONE 2007 2(4): e383.
-	Fischer, S., Brunk, B. P., Chen, F., Gao, X., Harb, O. S., Iodice, J. B., Shanmugam, D., Roos, D. S. and Stoeckert, C. J. [Using OrthoMCL to Assign Proteins to OrthoMCL-DB Groups or to Cluster Proteomes Into New Ortholog Groups](https://currentprotocols.onlinelibrary.wiley.com/doi/full/10.1002/0471250953.bi0612s35) Current Protocols in Bioinformatics. 2011 35:6.12.1–6.12.19. 
{.grid-list}