---
title: AACompIdent Tool
description: AACompIdent is a tool which allows the identification of a protein from its amino acid composition. It searches the Swiss-Prot and / or TrEMBL databases for proteins, whose amino acid compositions are closest to the amino acid composition given.
published: true
date: 2020-06-26T14:52:28.356Z
tags: tool, sequence analysis, sequence matching, proteins, sequence identity
editor: markdown
---

# AACompIdent Tool

> The AACompIdent tool can identify proteins by their AA composition. The program matches the percent empirically measured AA composition of an unknown protein against the theoretical percent AA compositions of proteins in the Swiss-Prot and/or TrEMBL databases. A score, which represents the degree of difference between the composition of the unknown protein and a protein in the database, is calculated for each database entry by the sum of the squared difference between the percent AA composition for all amino acids of the unknown protein and the database entry. All proteins in the database are then ranked according to their score, from lowest (best match) to highest (worst match). Estimated protein pI and MW, as well as species and keyword of interest can also be used in the identification procedure.
{.is-info}

 

## Website 

- [AACompIdent Tool *Main Page*](http://www.pdg.cnb.uam.es/cursos/Leon_2003/pages/visualizacion/programas_manuales/spdbv_userguide/us.expasy.org/tools/aacomp/index.html)
 {.links-list}

## Notes from the user
- This tool is meant for analysis of proteins for which the sequence is not already known
- User must provide a lot of information: PI, MW, Amino acid composition (in molar percentage), species, and separate information for a calibration protein

## Ease of use
> this tool is not easy to use due to the amount of prior knowledge the user needs before they can make use of the tool.


## Citations

- Wilkins M.R., Pasquali C., Appel R.D., Ou K., Golaz O., Sanchez J.C., Yan J.X., Gooley A.A., Hughes G., Humphery-Smith I., Williams K.L., Hochstrasser D.F. [From Proteins to Proteomes: Large Scale Protein Identification by Two-dimensional Electrophoresis and Amino Acid Analysis.](https://www.nature.com/articles/nbt0196-61) Bio/Technology 1996, 14, 61-65.
- Wilkins M.R., Ou K., Appel R.D., Sanchez J.C., Yan J.X., Golaz O., Farnsworth V., Cartier P., Hochstrasser D.F., Williams K.L., Gooley A.A. [Rapid protein identification using N-terminal "sequence tag" and amino acid analysis.](https://www.sciencedirect.com/science/article/abs/pii/S0006291X96906439) Biochem. Biophys. Res. Commun. 1996, 221, 609-613.
-	Wilkins M.R., Gasteiger E., Bairoch A., Sanchez J.-C., Williams K.L., Appel R.D., Hochstrasser D.F. [Protein Identification and Analysis Tools in the ExPASy Server in: 2-D Proteome Analysis Protocols (1998).](https://link.springer.com/protocol/10.1385/1-59259-890-0:571) Editor A.J. Link. Humana Press, New Jersey.
{.grid-list}