---
title: BSC6459 Introduction to Bioinformatics
description: 
published: true
date: 2024-03-11T01:26:07.029Z
tags: 
editor: markdown
dateCreated: 2024-01-23T19:14:46.497Z
---

# BSC64659 - Fundamentals of Bioinformatics
>  This course is an introduction to the basic bioinformatics tools used in computational biology for life science research. The course uses web-based resources that analyze gene and protein sequences as pertinent data examples. No programming skills are needed.
{.is-info}

**Student Learning Outcomes – After successful completion of this course, students will be able to:
1) Retrieve information on genes and proteins from biological and genomic databases.
2) Predict genes from DNA sequences.
3) Identify promoters and regulatory elements in DNA sequences
4) Analyze protein sequences
5) Compare protein and DNA sequences
6) Visualize and analyze protein structures
7) Construct and interpret simple phylogenies


### Module 1 - Bioinformatics: definitions and database primer

**Module Objectives**
- Define bioinformatics and it uses in biology
- Present the use of databases in Biology and how to find them
- Efficiently use Pubmed to find literature

> Bioinfornatics definition: [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics) gives a good summary in one sentence "Bioinformatics is an interdisciplinary field of science that develops methods and software tools for understanding biological data, especially when the data sets are large and complex". Modern biology has become a ["big data"](https://www.liebertpub.com/doi/full/10.1089/big.2020.0383) science and computational tools are needed to analyze  and make sense of all the different data types that are being generated. 
{.is-info}

#### Online Bioinformatic courses
> Numerous online resources are available for learning bioinformatics. A few free resources are listed below.
{.is-info}
- [**Bioinfo_courses I**](http://lectures.molgen.mpg.de/online_lectures.html)
- [**CourseArena**](https://www.coursearena.io/topic/free-bioinformatics-courses)
- [**A lecture series covering contemporary areas in genomics and bioinformatics**](http://www.genome.gov/12514288)

#### Depositories of online resources for biologists
>[Biological databases](https://en.wikipedia.org/wiki/Biological_database) are libraries of biological sciences, collected from scientific experiments, published literature, high-throughput experiment technology, and computational analysis. They can be classified by  many different criteria such as the types of data they cover, if they are primary data or curated, if they are general or specialized. The quality of the database depends on how often they are updated, the curation effort that goes in to them or how well they respond to user feedback. The perinity of databases is an [issue](https://academic.oup.com/nar/article/48/22/12523/6018434) as this requires long-term funding that is very difficult to secure.  Finding the best database to perform a task or access information is not easy a few staring points are listed below but generally, biologists have a set of databases they use on a regular basis for the majority of their tasks.
{.is-info}

- [**Biotools**](https://vdclab-wiki.herokuapp.com/databases/database_searches/biotools)
- [**MolBiol_Tools**](http://molbiol-tools.ca/)
- [**NAR database issue**](https://www.oxfordjournals.org/nar/database/c/)


#### Searching biological literature with Pubmed
> Pubmed is one of the databases that almost all biologists use to search and access biomedical literature.  It is also a good starting point for beginners to learn the basics of database searches such as the use of boolean operators, issues with names and spelling, or the use of advanced search tools. 
{.is-info}

- [**Litterature search Primer**](https://figshare.com/articles/presentation/Literature_Searching_Skills_and_Tools/7228721)
- [**Pubmed training**](https://learn.nlm.nih.gov/documentation/training-packets/T0042010P/)
- [**IntroPubmed Videos**](https://www.youtube.com/playlist?list=PL7dF9e2qSW0YkmxDTsUG6p4hJjYOPT0Uj)

For users who want to explore other literature resources than Pubmed a few are listed in this [Wiki](https://vdclab-wiki.herokuapp.com/en/literature-search).

### Module 2 - Information retrieval

**Module Objectives**
- Navigate a GenBank or SwissProt entry  and explore other databases from these entries 
- Extract DNA and Protein sequences from NCBI based on different criteria 
- Design complex queries to identify groups of entries at NCBI  ( and other databases)
- Find the genes of a specific  metabolic pathway in a specific  organism

> Extracting protein/gene sequences from databases is not trivial. First, names are not unique identifiers and mapping between different databases and/or objects is not well done or intuitive. [Ontology resources](https://geneontology.org/) are trying to homogenize names or give numbering systems such as the [EC](https://enzyme.expasy.org/) numbers for enzymes or the [TC](https://www.tcdb.org/) numbers for transporters.  This module focuses on extracting protein and gene sequences from NCBI and UniProt resources.
{.is-info}
- [**NCBI**](/resources/general_resources/NCBI-All-Resources)
- [**UniProt**](https://www.uniprot.org/)

#### Dealing with Input and Output formats
> The format of your input file is critical as most bioinformatic tools cannot deal with format errors. Make sure to understand the popular [FASTA](https://en.wikipedia.org/wiki/FASTA_format) and [GenBank](https://www.futurelearn.com/info/courses/bacterial-genomes-bioinformatics/0/steps/47012) formats. Tools to clean sequences up and convert one format to the other are also very useful.
{.is-info}
- [**Sequence Massager**](https://vdclab-wiki.herokuapp.com/e/en/sequence-manipulation/changing-format/NA-Sequence-Massager) is used  to clean up nucleic acid sequences
- [ **EMBOSS Seqret**](http-[**Uniprot**]s://www.ebi.ac.uk/jdispatcher/sfc/emboss_seqret) is used to change formats of sequences is part of the  [**Job Dispatcher**](https://www.ebi.ac.uk/jdispatcher/) platform provided by the EBI.
- [The SMS suite](http://www.bioinformatics.org/sms2/index.html) has reformatting tools

#### Dealing with redundancy
> With the ease of sequencing, some genomes get sequenced many times generating identical gene and protein objects. Databases have dealt with this in different ways. UniProt has [eliminated redundancy](https://www.uniprot.org/help/proteome_redundancy) by combining identical protein sequences in one unique entry. 
{.is-info}

#### Advanced searches and Cross-referencing  
> Advanced booleen searches are very powerful to find sets of genes/proteins using a wide variety of filters (taxonomy, size, annotation)  both in [Uniprot](https://www.uniprot.org/help/advanced_search) and NCBI. Every different database at NCBI has slightly different fields tgat can be searched see the one for [proteins](https://www.ncbi.nlm.nih.gov/protein/advanced) or [genes](https://www.ncbi.nlm.nih.gov/gene/advanced). All entries Uniprot and NCBI have multiple links to the same entry in other databases that can  provide similar or additional information such as [PDB](/structure/visualization-platforms/RCSB-PDB) or [BRENDA](/databases/data-integration/BRENDA-ENZYMES) or [KEGG](/databases/enzyme-pathway/KEGG-PATHWAY).
{.is-info}

### Module 3 - Pairwise Alignment
> Alignments are a powerful way to compare related DNA or protein sequences. They can be used to capture various facts about the sequences aligned, such as common evolutionary descent or common structural function. See good overall summary [HERE](https://www.ncbi.nlm.nih.gov/books/NBK464187/). We will focus first on pairwise sequence alignmemnts that are used to compare two sequences and search databases.  
{.is-info}

**Module Objectives**

- Compare and contrast the different methods used to align two sequences 
- Evaluate the validity of an alignment
- Perform sequence database searches and  interpret the results

#### Comparing two sequences
> Similarity matrices are the simplest way to align two sequences. These are called [**DotPlots**](https://en.wikipedia.org/wiki/Dot_plot_bioinformatics). 
{.is-info}
- [**DotLet** (for proteins only)](https://dotlet.vital-it.ch/)
- [**DotPlot tool 2**](https://en.vectorbuilder.com/tool/sequence-dot-plot.html)

> Many sequence pairwise alignment programs have been developed. They can be [**global or local**](https://bio.libretexts.org/Bookshelves/Computational_Biology/Book%3A_Computational_Biology_-_Genomes_Networks_and_Evolution_(Kellis_et_al.)/03%3A_Rapid_Sequence_Alignment_and_Database_Search/3.03%3A_Global_alignment_vs._Local_alignment_vs._Semi-global_alignment),use [**different matrices**](https://en.wikipedia.org/wiki/BLOSUM) for computing similarity scores between amino acids), be [**exact**](https://science.umd.edu/labs/delwiche/bsci348s/lec/Align.html) or [**heuristic**](https://science.umd.edu/labs/delwiche/bsci348s/lec/AlignHeuristic.html).  
{.is-info}

- [**Pairwise Sequence Alignment**](https://www.ebi.ac.uk/jdispatcher/psa) tools at EBI
- **Pairwise Sequence Alignment** for [**DNA**](http://www.bioinformatics.org/sms2/pairwise_align_dna.html) or [**Proteins**](http://www.bioinformatics.org/sms2/pairwise_align_protein.html)  tools at SMS
- Align two sequences using [**Blast**](https://blast.ncbi.nlm.nih.gov/Blast.cgi?BLAST_SPEC=blast2seq&LINK_LOC=align2seq&PAGE_TYPE=BlastSearch)

#### Warning 
> Any sequence can be aligned with any other sequence if enough gaps are allowed. 
{.is-info}

#### Searching databases
> Blast is the most popular program for searching databases. Input can be DNA or protein sequences.  Different databases can be sercahes and filters can be added to focus on specific taxonomic groups. This [**BLastFactSheet**](https://ftp.ncbi.nih.gov/pub/factsheets/HowTo_BLASTGuide.pdf)
{.is-info}
- [**BLast@NCBI**](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
- [**Blast@Uniprot**](https://www.uniprot.org/blast)