# RNA-seq

## Introduction

RNA-seq pipeline performs the following steps:
1. Quality control on fastq files (using FastQC && Trimmomatic && MultiQC)
2. Align the reads to the genome (using STAR) 
3. Quality check (using MultiQC) 
4. Filtering Bam files (using samtools)
5. Count reads in features (using featureCounts)
6. Normalize read counts (using DESeq2)
7. Calculate RPKMs (using edgeR/R base function)
8. Calculate TPMs (using R base function)
9. Perform DE analysis (using DESeq2)
10. Perform significant gene expression profile differences between experimental groups in time course (using maSigPro)


## EQUIPMENT
### Operating system

### Software
