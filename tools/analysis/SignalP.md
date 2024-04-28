---
title: SignalP 
description: Signal peptide and cleavage sites in gram+, gram- and eukaryotic amino acid sequences.
published: true
date: 2024-04-28T16:28:46.724Z
tags: tool, sequence analysis, proteins, prediction, protein domain
editor: markdown
dateCreated: 2020-04-28T18:25:09.509Z
---

# SignalP - 6.0

> The SignalP server predicts the presence of signal peptides and the location of their cleavage sites in proteins from Archaea, Gram-positive Bacteria, Gram-negative Bacteria and Eukarya. 
&NewLine;
In Bacteria and Archaea, SignalP 6.0 can discriminate between five types of signal peptides:

- Sec/SPI: "standard" secretory signal peptides transported by the Sec translocon and cleaved by Signal Peptidase I (Lep)
-  Sec/SPII: lipoprotein signal peptides transported by the Sec translocon and cleaved by Signal Peptidase II (Lsp)
- Tat/SPI: Tat signal peptides transported by the Tat translocon and cleaved by Signal Peptidase I (Lep)
- Tat/SPII: Tat lipoprotein signal peptides transported by the Tat translocon and cleaved by Signal Peptidase II (Lsp)
- Sec/SPIII: Pilin and pilin-like signal peptides transported by the Sec translocon and cleaved by Signal Peptidase III (PilD/PibD) 

Additionally, SignalP 6.0 predicts the regions of signal peptides. Depending on the type, the positions of n-, h- and c-regions as well as of other distinctive features are predicted.
SignalP 6.0 is based on a transformer protein language model with a conditional random field for structured prediction. 

{.is-info}
 

## Website 

- [SignalP - 5.0 *Main Page*](https://services.healthtech.dtu.dk/service.php?SignalP-5.0)
- [SignalP - 6.0 *Main Page*](https://services.healthtech.dtu.dk/services/SignalP-6.0/)
 {.links-list}

## Notes from the user
- Results are given as a graph which show probability of each section of a sequence belonging to a signaling peptide
- There is an extensive guide to help the user understand their results


## Ease of use

The user only needs to provide a protein sequence and select the report length to use the tool. The results are simple and quickly identify Sec or Tat signals and cleavage sites. 


## Citation 

- Nielsen, H., Tsirigos, K. D., Brunak, S., & von Heijne, G. (2019). [A brief history of protein sorting prediction.](https://link.springer.com/article/10.1007/s10930-019-09838-3) The protein journal, 38(3), 200-216.
{.grid-list}
