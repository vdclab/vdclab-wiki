---
title: Fundamental Definitions
description: Key concepts and terms covered in the official bioinformatics introductory course
published: true
date: 2023-08-05T15:13:08.788Z
tags: recommended, favorites, workflows
editor: markdown
dateCreated: 2023-08-05T14:30:11.848Z
---

# Fundamental Definitions
### Homology and Orthology in Sequence Analysis
***Why compare DNA/protein sequences?***
The relationship between structure and function is a principle we can observe across biological systems, structures, and mechanisms (e.g., evolutionary theory). ***Therefore, similarities between structures may also imply similarities between functions***.
If determining function is our ultimate goal in bioinformatics (as it often is), comparing sequence identities and other sequence-level characteristics can be a good place to start.

***Sequence Similarity (Identity) and Homology***
Methods implemented in bioinformatics are often dependent upon ***similarity-based comparisons of biomolecular sequences***. Before one can proceed to structure or function, characteristics of the sequence must first be analyzed.

High sequence similarity is used ***to infer homology*** (i.e., that the given sequences share a common ancestral sequence).

An inference of homology can then be used ***to infer orthology*** (i.e., in terms of their relation, sequences are inferred to be a result of a speciation event, and, therefore, likely share the same function).

- ***insert diagram(s) illustrating homology, orthology as applied to comparative genomics***



> The ***true evolutionary history of sequences*** (and, therein, their relationship to one another) can sometimes be hidden depending on the scale and comprehensiveness of the analyses being performed.
**Paralogs are a frequent cause of incorrect ortholog inferences**.
Paralogs are ***homologous sequences resulting from a gene duplication event***. These events can occur at any time along a protein family's evolutionary history (e.g., before or after a speciation event), and are not necessarily limited in the number of times they may occur over the course of that history. As a result, ***paralogs can easily be mistaken for orthologs when performing similarity-based investigations***.
{.is-warning}




### Databases, Online Resources

