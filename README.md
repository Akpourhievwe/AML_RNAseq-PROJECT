# AML RNA-seq Differential Gene Expression Analysis

## Project Overview
This is a personal RNA-sequencing analysis project investigating differences in gene expression between acute myeloid leukemia (AML) samples and healthy bone marrow controls.

## Research Question
Which genes are differentially expressed in AML bone marrow samples compared with healthy controls?

## Dataset
- GEO accession: GSE138702
- SRA project: SRP225068
- Organism: Homo sapiens
- Sequencing type: Paired-end RNA-seq
- Sequencing platform: Illumina HiSeq 3000
- Reference genome reported by GEO: GRCh37/hg19

## Preliminary Sample Information
The GEO series currently lists 19 samples:
- 9 AML samples
- 10 healthy control samples

The study's overall design describes 10 AML patients and 10 healthy controls. This discrepancy will be investigated before finalizing the sample selection.

## Planned Analysis Workflow
1. Dataset and metadata validation
2. SRA data acquisition
3. FASTQ quality control using FastQC and MultiQC
4. Read trimming using Trimmomatic
5. Read alignment using HISAT2
6. Alignment quality assessment using SAMtools
7. Gene-level read counting using featureCounts
8. Differential gene expression analysis using R
9. Biological interpretation and visualization

## Tools
- Linux
- Conda
- SRA Toolkit
- FastQC
- MultiQC
- Trimmomatic
- HISAT2
- SAMtools
- Subread / featureCounts
- R

## Project Status
GitHub repository and initial project structure created.
Dataset validation and analysis are ongoing.

## Data Source
NCBI Gene Expression Omnibus:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE138702

## Disclaimer
This is an educational and research learning project. Findings will be interpreted in the context of the study design and available sample metadata.
