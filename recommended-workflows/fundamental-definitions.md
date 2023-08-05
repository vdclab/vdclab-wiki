---
title: Fundamental Definitions
description: Key concepts and terms covered in the official bioinformatics introductory course
published: true
date: 2023-08-05T16:13:07.584Z
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
Figure legend [[ref]](link)


> The ***true evolutionary history of sequences*** (and, therein, their relationship to one another) can sometimes be hidden depending on the scale and comprehensiveness of the analyses being performed.
**Paralogs are a frequent cause of incorrect ortholog inferences**.
Paralogs are ***homologous sequences resulting from a gene duplication event***. These events can occur at any time along a protein family's evolutionary history (e.g., before or after a speciation event), and are not necessarily limited in the number of times they may occur over the course of that history. As a result, ***paralogs can easily be mistaken for orthologs when performing similarity-based investigations***.
{.is-warning}




### Databases, Online Resources: How to Approach
Increasingly, many bioinformatic tools and databases are accessible via internet browser through webservers or web portals. However, not all tools are created equal in their veracity and validity. In our lab, we emphasize that no tool should be used alone for finalizing conclusions about a protein's function; that is, ***it is essential that multiple tools and data sources be used and their results compared for more comprehensive, accurate bioinformatic investigations***. It should also be noted that, while some resources are more reliable and more up-to-date than others, ***it is always important that any bioinformatics user approach even their favorite resources with a critical eye***.

***Online Resources, Reliability and Longevity***
The lifetime of online bioinformatic resources was recently reported to be surprisingly low and that the continued accessibility was found to be positively correlated with the number of user citations [[2]](https://academic.oup.com/nar/article/48/22/12523/6018434). To date, the varied accessibility and sustained functionality of web resources continues to be a problem for biological data reuse and can be an important factor influencing in the successes of bioinformatic analyses.

Although not structured by modularized workflows and lacking expert curation, the [Database Commons](https://ngdc.cncb.ac.cn/databasecommons/) maintained by the China National Center for Bioinformation and National Genomics Data Center is an impressive resource, actively updating and electronically monitoring an immense catalog of biological databases and tools maintained around the globe. There, citation histories and activity for nearly 6k databases can be browsed, filtered, and explored.


