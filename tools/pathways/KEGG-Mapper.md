---
title: KEGG Mapper
description: KEGG Mapper is a collection of tools for KEGG mapping: most popular KEGG pathway mapping, as well as BRITE mapping and MODULE mapping.
published: true
date: 2020-05-31T20:44:04.463Z
tags: annotation, annotation tools, tool, metabolic reconstruction, data visualization, mapping, metabolic pathways, 2020, id mapper
---

# KEGG Mapper

> KEGG Mapper is a collection of tools for KEGG mapping: most popular KEGG pathway mapping, as well as BRITE mapping and MODULE mapping. In this new release, fourteen existing tools were reorganized into just five tools. Three of them, `Reconstruct Pathway`, `Search Pathway` and `Search&Color Pathway` allow multiple mapping operations to be done at the same time. The result is shown in multiple tabs in the result page. The other two are specialized tools, `Color Pathway` and `Join Brite`, for mapping against a single pathway map or a single brite hierarchy/table file.
{.is-info}

## Website
- [KEGG Mapper *Main Page*](https://www.genome.jp/kegg/mapper.html)
- [Reconstruct Pathway *Annotation tool*](https://www.genome.jp/kegg/tool/map_pathway.html)
- [Search Pathway *Basic mapping tool*](https://www.genome.jp/kegg/tool/map_pathway1.html)
- [Search&Color Pathway *Advanced mapping tool*](https://www.genome.jp/kegg/tool/map_pathway2.html)
- [Color Pathway *Multiple coloring for mapping*](https://www.genome.jp/kegg/tool/map_pathway3.html)
- [Join Brite *Mapping on Brite files*](https://www.genome.jp/kegg/tool/map_brite3.html)
- [Convert ID *ID mapper to KEGGids*](https://www.kegg.jp/kegg/tool/conv_id.html)
- [Annotate Sequence *Interface to BlastKoala in KEGG mapper*](https://www.kegg.jp/kegg/tool/annotate_sequence.html)
{.links-list}

## Notes from Users

### Reconstruct Pathway

- Take a table of KEGG KO number as entry (see example).
- Can take multiple organisms with the # separation (see example 2).
- Get a result on KEGG Metabolic map, Brite and Modules.

### Search Pathway

- Take different KEGG object to map them.
- Same type of result as previous tool.

### Search&Color Pathway

- Same tool as above but you can specify colors.

### Color Pathway

- Color chosen pathway.
- Choose color depnding on input (see examples).

### Join Brite

- Used to add a column of your choice to the Brite tables.
- You need to be familiar with the Brite tables first.

### Convert ID

- Convert NCBI or Uniprot Id to KO Id.

### Annotate Sequence

- Enter a protein multifasta.
- Sequenced are annotated and mapped to the pathways.

## Ease of use

- As all KEGG tools, it can be confusing at first.
- Try with the provided examples to get familiar with the tools.

> Easy to get the KO id with their convert ID tool.
{.is-success}

## Citation
- Kanehisa, M. and Sato, Y. (2020) [KEGG Mapper for inferring cellular functions from protein sequences.](https://onlinelibrary.wiley.com/doi/full/10.1002/pro.3711) Protein Sci. 29, 28-35.
{.grid-list}