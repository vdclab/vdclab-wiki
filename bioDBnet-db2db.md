---
title: bioDBnet Database to Database Conversions
description: db2db allows for conversions of identifiers from one database to other database identifiers or annotations.
published: true
date: 2020-04-18T02:11:18.555Z
tags: annotation, tool, gene, protein, 2009
---

# bioDBnet Database to Database Conversions

> BioDBnet is a network of the major biological databases. There is a vast amount of infomation available in various formats and in various scattered resources. They tried to put all this information together and make it available through an easy to use web resource. The major advantages that bioDBnet offers compared to similar resources is the simplicity of their model, the number and types of databases integrated, support for batch conversions and the integration process itself. bioDBnet is created in such a way that it picks up all the database updates seamlessly.
{.is-info}

## Website

- [bioDBnet *Main Page*](https://biodbnet-abcc.ncifcrf.gov/)
- [db2db *Main Tool*](https://biodbnet-abcc.ncifcrf.gov/db/db2db.php)
- [dbWalk *db2db choose your path*](https://biodbnet-abcc.ncifcrf.gov/db/dbWalk.php)
- [dbReport *db2db all output*](https://biodbnet-abcc.ncifcrf.gov/db/dbReport.php)
- [dbFind *db2db mixed or unknown input*](https://biodbnet-abcc.ncifcrf.gov/db/dbFind.php)
- [dbOrtho *orthologues search*](https://biodbnet-abcc.ncifcrf.gov/db/dbOrtho.php)
- [dbAnnot *genome annotation*](https://biodbnet-abcc.ncifcrf.gov/db/dbAnnot.php)
- [dbOrg *precomputed convertion of whole organisms*](https://biodbnet-abcc.ncifcrf.gov/db/dbOrg.php)
- [Help *Examples of Use*](https://biodbnet-abcc.ncifcrf.gov/dbInfo/examples.php)
- [FAQs *Frequently Asked Questions*](https://biodbnet-abcc.ncifcrf.gov/dbInfo/faq.php)
{.links-list}

## Notes from Users 
### db2db
Enter your list of IDs, select the database they come from, then the database Id you want them converted to. The result comes as a table you can export.
### dbWalk
Same tool as db2db, except that you choose the path of convesrion from a database to another. Path are easy to add and remove but a comprehension of database organisation is required to use this tool.
### dbReport
Same tool as db2db, except that you don't choose the output database. Instead you get the ID in all databases.
### dbFind
Same tool as db2db, except that you don't specify the input database. The tool will automatically detect the database of origins. It also allows to have a list of mixed origins for the IDs. Sometimes it is the only tool that allows to map Ids.
### dbOrtho
Same tool as db2db, except that you can specify your species of entry and specify a species of output for orthologue searches.
### dbAnnot
Use the dbFind tool to match genes in a genome of your choice (TaxId from NCBI as entry).
### dbOrg
precuputed converstion of whole genome of specific organisms.
## Ease of Use
All these tools are really easy to use, and the output is also really easy to get.
## Citation

- Mudunuri,U., Che,A., Yi,M. and Stephens,R.M. (2009) [bioDBnet: the biological database network.](http://bioinformatics.oxfordjournals.org/content/25/4/555.full.pdf+html) Bioinformatics, 25, 555-556.
{.grid-list}