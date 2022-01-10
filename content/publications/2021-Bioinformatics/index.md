---
title: "An accurate method for identifying recent recombinants from unaligned sequences"
author: "Qian Feng, Kathryn E. Tiedje, Shazia Ruybal-Pesántez, Gerry Tonkin-Hill, Michael F. Duffy, Karen P. Day, Heejung Shim, Yao-ban Chan"
date: '2021-12-27'
slug: recent-recombinants
alias:
  - /publications/2021-Bioinformatics/
categories:
  - Research
tags:
doi: ''
publishDate: '2021-12-27'
publication_types:
  - '2'
excerpt: 'We developed a new method to detect recent recombinant sequences without the need for a reference panel, and demonstrate its application to malaria parasite *var* genes that are highly recombinogenic. This article has been accepted in *Bioinformatics*.'
subtitle: 'We developed a new method to detect recent recombinant sequences without the need for a reference panel, and demonstrate its application to malaria parasite var genes that are highly recombinogenic.'
featured: yes
links:
# - icon: doi
#   icon_pack: ai
#   name: Publication
#   url: 
---

**This article has been accepted in *Bioinformatics* **
## Abstract 

#### Motivation: 
Recombination is a fundamental process in molecular evolution, and the identification of recombinant sequences is thus of major interest. However, current methods for detecting recombinants are primarily designed for aligned sequences. Thus they struggle with analyses of highly diverse genes, such as the *var* genes of the malaria parasite *Plasmodium falciparum*, which are known to diversify primarily through recombination.

#### Results: 
We introduce an algorithm to detect recent recombinant sequences from a dataset without a full multiple alignment. Our algorithm can handle thousands of gene-length sequences without the need for a reference panel. We demonstrate the accuracy of our algorithm through extensive numerical simulations; in particular, it maintains its effectiveness in the presence of insertions and deletions. We apply our algorithm to a dataset of 17,335 DBLα types in *var* genes from Ghana, observing that sequences belonging to the same ups group or domain subclass recombine amongst themselves more frequently, and that non-recombinant DBLα types are more conserved than recombinant ones.

#### Availability: 
Source code is freely available at https://github.com/qianfeng2/detREC_program.
