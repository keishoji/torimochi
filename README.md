# Overview:

This repository contains the code needed to reproduce the result of the following manuscript:

Keisuke Shoji, Yusuke Umemura, Susumu Katsuma, Yukihide Tomari, The piRNA cluster torimochi is an expanding transposon in cultured silkworm cells. 
https://www.biorxiv.org/content/10.1101/2022.09.07.506900v1
(published in PLOS genetics)
https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1010632

# Contents:

### (0)Data_Preparation
Correspondence to the accession numbers of the data used in the analysis
For small RNA libraries, removal of adapter sequences

### (1)known_torimochi
Analysis using torimochi sequences present in the silkworm genome
This script corresponds to Fig. 1 and S1 in the paper
### (2)new_torimochi
Analysis using some specific torimochi sequences identified using the nanopore sequencer.
This script corresponds to Fig. 2 and S3 in the paper
### (3)new_insertions
Analysis using a large number of transposition sequences identified using the nanopore sequencer.
This script corresponds to Fig. 3, 4, S4 and S5 in the paper
### (4)differenciated_cells
Analysis of BmN4 cells with adipocyte differentiation system
This script corresponds to Fig. 5 in the paper
### (5)Sibling_cells
Comparative genomic analysis of sibling BmN4 cells
This script corresponds to Fig. S6 in the paper

## Tools:
Data analysis was performed with blast+, Bowtie, bwa, bedtools, cutadapt, hisat2, linux command, pigz, R, Rscript, samtools, seqkit, snp-sites and svim.
R packages used include: Biostrings, circlize, ggplot2, ggsci, ggthemes, RcolorBrewer and Rsamtools.


### The version of tools in PC for Analysis
BLAST 2.13.0+
bowtie version 1.2.3
bwa 0.7.17-r1198-dirty
bedtools v2.29.2
cutadapt 2.6 with Python 3.7.0
hisat2 version 2.1.0
pigz 2.4
R version 4.1.3 
R scripting front-end version 4.1.3
samtools Version: 1.7 
seqkit Version: 0.15.0
snp-sites 2.5.1
svim 1.3.0

Biostrings 2.62.0
circlize 0.4.15
ggplot2 3.3.6
ggthemes 4.2.4
Rsamtools 2.10.0
 
### The version of tools in macbook for graph
R version 3.4.0
Biostrings 2.46.0
circlize 0.4.8
ggplot2 3.2.1
ggsci 2.9
ggthemes 4.2.0
RcolorBrewer 1.1.2
Rsamtools 1.30.0
