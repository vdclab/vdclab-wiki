---
title: BLAT Search Genome
description: BLAT on DNA is designed to quickly find sequences of 95% and greater similarity of length 25 bases or more.
published: true
date: 2020-06-10T15:31:30.295Z
tags: tool, sequence similarity, data visualization, mapping, genome, eukaryota, 2002
editor: markdown
---

# BLAT Search Genome

> BLAT on DNA is designed to quickly find sequences of 95% and greater similarity of length 25 bases or more. It may miss more divergent or shorter sequence alignments. It will find perfect sequence matches of 20 bases. BLAT on proteins finds sequences of 80% and greater similarity of length 20 amino acids or more. In practice DNA BLAT works well on primates, and protein BLAT on land vertebrates.
&NewLine;
BLAT is not BLAST. DNA BLAT works by keeping an index of the entire genome in memory. The index consists of all overlapping 11-mers stepping by 5 except for those heavily involved in repeats. The index takes up about 2 gigabytes of RAM. RAM can be further reduced to less than 1 GB by increasing step size to 11. The genome itself is not kept in memory, allowing BLAT to deliver high performance on a reasonably priced Linux box. The index is used to find areas of probable homology, which are then loaded into memory for a detailed alignment. Protein BLAT works in a similar manner, except with 4-mers rather than 11-mers. The protein index takes a little more than 2 gigabytes.
{.is-info}



## Website

- [BLAT Search Genome *Main Page*](http://genome.ucsc.edu/cgi-bin/hgBlat?hgsid=412713987_NrFiBsC7HAfLzfiAeKNgr11VBglP&command=start)
{.links-list}

## Note from Users
- Mostly for model Eukaryotic genomes but E. coli is available.
- Not sensitive with bacterial homologs.

## Ease of use
- Input your sequence.
- Choose to have a list of results or the first result page (I am feeling lucky button).
- Get a graphic reprenstation of the chromosomal position and other features you can choose.


## Citation

- Kent WJ. [BLAT - the BLAST-like alignment tool.](https://genome.cshlp.org/content/12/4/656.short) Genome Res. 2002 Apr;12(4):656-64.
{.grid-list}