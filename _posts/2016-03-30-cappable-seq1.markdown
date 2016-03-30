---
layout: post
title: "Considerations for Cappable-seq as a method for whole transcriptome sequencing of prokaryotes."
date: "2016-03-15 12:02:16 -0400"
categories: jekyll update
published: true
---

Cappable-seq can be used as a method to enrich for bacterial mRNA from pure culture or a mixed population of eukaryotic and prokaryotic RNA, effectively depleting capped mRNA from eukaryotes and ribosomal RNA from both kingdoms. This enrichment is based on the selective capture of 5’ triphosphorylated RNA typically found with all prokaryotic primary transcripts. Eukaryotic mRNA transcripts and ribosomal RNA from both eukaryotes and prokaryotes do not have triphosphorylated ends and therefore will be significantly depleted. Contrary to hybridization methods that are both specific to only only a few targets species and have off target effects, Cappable-seq universally depletes eukaryotic and ribosomal RNA no matter the species. 


Here are a few considerations to take into account before opting for Cappable-seq :

[1] Capturing of the 5’ end . 
The method captures the prokaryotic transcripts by their 5’end. If the RNA sample is not degraded, the full length transcript will be captured with no or little little bias towards the 5’ end. However, if the RNA sample has been degraded, Cappable-seq will result in a bias for the 5’ end of transcripts.

[2] Triphosphorylated RNA in eukaryotes. 
While the vast majority of the 5’ end of transcripts in eukaryotes are either capped or 5’ monophosphate, some minor quantity of eukaryotic transcripts will be 5' triphosphate and enriched together with the bacterial transcripts.  Those are transcripts derived from the RNA polymerase I and III such as 5S, 7SK.

[3] Library construction.
The library construction from full length RNA will be different from the strategy described in Ettwiller et. al., for TSS determination. Once the captured RNA is removed from the streptavidin beads and purified, the RNA is available to use your preferred protocol for library preparation

[4] Primary transcripts.
Conventional RNA-seq experiments determine the relative amounts of all RNA’s in a sample. On the other hand Cappable-seq identifies and quantifies the primary transcriptome by distinguishing the initiating 5’ nucleotide incorporated by the RNA polymerase from all the other 5’ ends that arise due to processing. Therefore the transcriptome defined by Cappable-seq represents the primary transcriptome. 





