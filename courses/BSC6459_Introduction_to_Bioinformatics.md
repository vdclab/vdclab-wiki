---
title: BSC6459 Introduction to Bioinformatics
description: 
published: true
date: 2024-03-15T01:30:33.532Z
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
- [**The SMS suite**](http://www.bioinformatics.org/sms2/index.html) has reformatting tools

#### Dealing with redundancy
> With the ease of sequencing, some genomes get sequenced many times generating identical gene and protein objects. Databases have dealt with this in different ways. UniProt has [eliminated redundancy](https://www.uniprot.org/help/proteome_redundancy) by combining identical protein sequences in one unique entry. NCBI has  dealt by using [WP records](https://ftp.ncbi.nlm.nih.gov/refseq/release/announcements/WP-proteins-06.10.2013.pdf), then [Identical Protein Reports](https://www.ncbi.nlm.nih.gov/books/NBK431037/#news_09-09-2014-identical-protein-report-display-setting) and finally [Identical Protein Groups (IPG)](https://ncbiinsights.ncbi.nlm.nih.gov/2017/07/26/identical-protein-groups-non-redundant-access-to-protein-records/).
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
- [**PRSS**](/alignment/two-sequences-alignment/PRSS) computes the statistical significance of an alignment
#### Similarity scores are not homology scores 
> Any sequence can be aligned with any other sequence if enough gaps are allowed.  An alignment score is a measure of the similarity of the two sequences using a specific algorithm and parameters. It is  NOT a measure of homology even if it can be used as one of many criteria to infer [**homology, orthology. or paralogy**](https://bio.libretexts.org/Bookshelves/Microbiology/Microbiology_(Boundless)/07%3A_Microbial_Genetics/7.13%3A_Bioinformatics/7.13C%3A_Homologs_Orthologs_and_Paralogs)
{.is-info}

#### Searching databases
> Blast is the most popular program for searching databases. Input can be DNA or protein sequences.  The output gives the top-scoring pairwise alignment between the input sequence and individual database sequences. Different databases can be searched and filters can be added to focus on specific taxonomic groups. This [**BLastFactSheet**](https://ftp.ncbi.nih.gov/pub/factsheets/HowTo_BLASTGuide.pdf) is a good starting point. 
{.is-info}
- [**BLast@NCBI**](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
- [**Blast@Uniprot**](https://www.uniprot.org/blast)
- [**Blast@Kegg**](https://www.genome.jp/tools/blast/)


> Two scores are given for every output sequence; the Bit score is a similarity score. The e-value is the probability of getting this score by chance and it will vary with the size of the queried database. More details in these videos: BLAST Results: Expect Values, [Part 1](https://www.youtube.com/watch?v=ZN3RrXAe0uM)  & [Part 2](https://www.youtube.com/watch?v=dzRq-5BrGD4).
{.is-info}

> WARNING: With the number of sequences deposited in Genbank, using Blast with default parameters is nearly useless. Using smaller databases, excluding specific taxa  or focusing on reference or model oragnisms are different ways to get around this issue.
{.is-info}

> Alternatives to blast to search database exist, The best known is  [**FASTA**](https://www.ebi.ac.uk/jdispatcher/sss/fasta) that actually preceeded Blast .
{.is-info}

> Cool tool to find the litterature on potential homologs of a given imput sequence by using  [PaperBlast](/literature-search/PaperBLAST) 

### Module 4 - Multiple Sequence Alignment (MSA)

**Module Objectives**
- Use different methods to capture sequences, build and edit a Multiple Sequence Alignment (MSA) 
- Interpret the biological meaning of an MSA 
- Identify domains, profiles, and motifs in sequences and build logos -  Find distant homologs of a specific protein

> To generate a useful alignment a set of phylogenetically diverse homologous sequences have to be gathered in Fasta format and used as input in the alignment programs. (Note: headers that are too long can get cut and if the beginning are identical this might lead to errors. Hidden characters can also cause errors. It is always useful to use text editors such as TextEdit or Notepad++).
{.is-info}
- [**CustalOmega**](http://www.ebi.ac.uk/Tools/msa/clustalo/)
- [**T-coffee**](/alignment/multiple-alignment/T-COFFEE)
- [**Multialin**](http://multalin.toulouse.inra.fr/multalin/)
- [**Compilation of MSA programs @EBI**](https://www.ebi.ac.uk/jdispatcher/msa)

> Different tools can be used to edit alignments. [JalView](/visualization/data-visualization/Jalview) is a popular option. 
{.is-info}

To visualize alignments this tool for EBI  http://www.ebi.ac.uk/Tools/msa/mview/  .

>Multiple alignments are the foundational tools to classify proteins A good primer on [protein classification @EBI](https://www.ebi.ac.uk/training/online/courses/protein-classification-intro-ebi-resources/) 
{.is-info}

- [**Prosite**](/tools/analysis/ExPASy-PROSITE)
- [**InterPro**](https://www.ebi.ac.uk/interpro/)
- [**CDD**](/tools/analysis/NCBI-Conserved-Domains)

> Tools to visualize conserved motifs  in proteins and DNA 
{.is-info}
- [**WebLogo**](http://weblogo.berkeley.edu/)
- [**WebLogo3**](/tools/sequence-logos/WebLogo3)
- [**MEME**](/tools/analysis/The-MEME-Suite)

> The Profiles, Motifs, or HMMs allow to find remote homologs in database searches.
{.is-info}
- [**HHMER**](https://www.ebi.ac.uk/Tools/hmmer/search/phmmer)
- [**PsiBlast**](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE=Proteins&PROGRAM=blastp&RUN_PSIBLAST=on)


