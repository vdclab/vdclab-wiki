---
title: Basics of Information Retrieval
description: Based on the second module of the introductory bioinformatics course (UF, BSC6459), in addition to some components/themes of module 1
published: true
date: 2023-09-18T17:14:34.667Z
tags: recommended, favorites, workflows, information retrieval, databases
editor: markdown
dateCreated: 2023-08-22T13:54:13.003Z
---


# What is Bioinformatics?

Bioinformatics, broadly, is a subfield of biology defined by the use of interdisciplinary technological approaches to extract information from biological data and to formulate biological knowledge and understanding from those observations. In 1970, Paulien Hogeweg and Ben Hesper defined bioinformatics as "the study of information processes in biotic systems" (PMID: 14630646), but, with the advancements of computing, the field of bioinformatics has seen colossal changes since those early days.

Because this field is so diverse and is built on the motivation of finding practical data solutions, often computational ones, the strategies used by those who practice bioinformatics can look very different between different backgrounds of training, with some bioinformaticians preferring tool-making and others preferring a combined approach of leveraging bioinformatic tools for pairings of *in silico* and *in vivo* functional genomics.

# Sequence Databases
Regardless of the bioinformatic subfield or practical definition, biomolecular sequence data has always been at the core of, both, the field's origins and its current state of practice. By far, biomolecular sequences make up the greatest share of available biodata available today. Today, approximately 1.5 million nucleotide sequences are submitted to the DDBJ every day (data: [DDBJ website](https://www.ddbj.nig.ac.jp/statistics/index-e.html); calculation, diff. between releases, r131 and r130).
## Genome/Assembly DBs 
**neglecting organism-specific Dbs*

- [JGI GOLD](https://gold.jgi.doe.gov/)
- [NCBI Genome](https://www.ncbi.nlm.nih.gov/genome/)
- [gnomAD](https://gnomad.broadinstitute.org/)
- [GenomeNet Database](https://www.genome.jp/)
- [PlantGDB](https://www.plantgdb.org/)
- [IGSR](https://www.internationalgenome.org/data/) (International Genome Sample Resource)
- [MBGD](https://mbgd.nibb.ac.jp/) (Microbial Genome Database)
- [Aliiance of Genome Resources](https://www.alliancegenome.org/)
- [BIGSdb](https://pubmlst.org/software/bigsdb) (Bacterial Isolate Genome Sequence Database)
- []()




## Nucleotide/Gene DBs

- [The International Nucleotide Sequence Database Collaboration](https://www.insdc.org/)
-- [NCBI](https://www.ncbi.nlm.nih.gov/) (National Center for Biotechnology Information)
---- [NCBI Gene](https://www.ncbi.nlm.nih.gov/gene)
---- [GenBank](https://www.ncbi.nlm.nih.gov/genbank/)
---- [BioSample/BioProject](https://www.ncbi.nlm.nih.gov/biosample)
---- [SRA](http://www.ncbi.nlm.nih.gov/sra) (Sequence Read Archive)
-- [DDBJ](https://www.ddbj.nig.ac.jp/index-e.html) (DNA Databank of Japan)
---- [SRA](http://trace.ddbj.nig.ac.jp) (Sequence Read Archive)
-- [EMBL-EBI](https://www.ncbi.nlm.nih.gov/biosample)
---- [ENA](https://www.ebi.ac.uk/ena/browser/home) (European Nucleotide Archive, EMBL-EBI)
---- [BioSamples](https://www.ebi.ac.uk/biosamples/)
---- [EBI Patent Sequences](https://www.ebi.ac.uk/patentdata/nucleotides)
---- [SRA](http://www.ebi.ac.uk/ena) (Sequence Read Archive)
-- [EGA](https://ega-archive.org/datasets/) (European Genome-phenome Archive)

- [PLSDB](https://ccb-microbe.cs.uni-saarland.de/plsdb) (Plasmid Database)
- [ENSEMBL Database](https://useast.ensembl.org/index.html)
- [KEGG](https://www.kegg.jp/)


## Protein DBs

- [CaZY](http://www.cazy.org/) (**Ca**rbohydrate-active En**zy**mes Database)
- [DescribePROT](http://biomine.cs.vcu.edu/servers/DESCRIBEPROT/main.php) (**D**atabas**e** of **S**tru**c**tu**r**e and Funct**i**on Residue-**b**ased Pr**e**dictions of **Prot**eins)
- [NCBI Protein](https://www.ncbi.nlm.nih.gov/protein)
- [NrichD Database](http://proline.biochem.iisc.ernet.in/NRICHD/)
- [PIR](https://proteininformationresource.org/) (Protein Information Resource)
- [TCDB](https://tcdb.org/) (Transporter Classification Database)
- [Uniclust](https://uniclust.mmseqs.com/)
- [UniProtKB](https://www.uniprot.org/)
--- [UniParc](https://www.uniprot.org/uniparc/?query=*)
--- [UniRef](https://www.uniprot.org/uniref/?query=*)
--- [UniSave](http://www.ebi.ac.uk/uniprot/unisave/app/#/)
- [CyBase](http://www.cybase.org.au/) (Database of Cyclic Proteins)
- [MemMoRF](https://memmorf.hegelab.org/) (Database of Membrane Associated Disordered Protein Regions)
- [MobiDB](https://mobidb.bio.unipd.it/) (Database of Protein Disorder and Mobility Annotations)
- [CATH/Gene3D](https://www.cathdb.info/)

**Orthology Systems**
- [SMART](http://smart.embl.de/)
- [CDD](https://www.ncbi.nlm.nih.gov/Structure/cdd/cdd.shtml) (Conserved Domain Database)
- [EggNOG](http://eggnog6.embl.de/)
- [MyHits](https://myhits.sib.swiss/)
- [InParanoidDB](https://inparanoidb.sbc.su.se/)
- [iProClass](https://proteininformationresource.org/pirwww/dbinfo/iproclass.shtml)
- [LenVarDB](http://caps.ncbs.res.in/lenvardb/) (Database of Length Variant Protein Domains)
- [OMA](https://omabrowser.org/oma/home/)
- [OrthoDB](https://www.orthodb.org/)
- [OrthoInspector]()
- [OrthoMCL]()
- []()

**Analog Detection**
- [MALISAM](http://prodata.swmed.edu/malisam/) (**M**anual **Ali**gnments of **S**tructurally **A**nalogous **M**otifs)

**Proteomes**
- [Proteome Analyst](http://pa.wishartlab.com/pa/)
- [Proteomes (UniProt)](https://www.uniprot.org/proteomes?query=*)

**Structures**
- [RCSB-PDB](https://www.rcsb.org/)
- [PDBe (EMBL-EBI)](https://www.ebi.ac.uk/pdbe/)
- [PDBj](https://pdbj.org/)
- [BMRB](https://bmrb.io/) (Biological Magnetic Resonance Data Bank)
- [EMDB (EMBL-EBI)](https://www.ebi.ac.uk/emdb/) (Electron Microscopy Data Bank)

**Interactions**
- [BindingDB](https://www.bindingdb.org/rwd/bind/index.jsp)
- [PPT-DB](http://www.pptdb.ca/) (The Protein Property Prediction & Testing Database)

**Literature Search**
- [iProClass](https://research.bioinformatics.udel.edu/iprolink/)
- [PaperBLAST](https://papers.genomics.lbl.gov/cgi-bin/litSearch.cgi)
- [Seq2Ref](http://prodata.swmed.edu/seq2ref/)

## Expression DBs 

- [Expression Atlas](https://www.ebi.ac.uk/gxa/home) (EMBL-EBI)
- [PRODORIC](https://www.prodoric.de/)
- [CoXPresDb](https://coxpresdb.jp/)
- [ArrayExpress (BioStudies.)](https://www.ebi.ac.uk/biostudies/arrayexpress)
- RegulonDB
- 


