# Multi-omics analysis for identifying tumor breast cancer subtypes
Data science student's project

## Data availiability
The RNA-Sequencing can be downloaded from Gene Expression Omnibus (accession number [GSE62944](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62944)). 
Methylation and clinical data can be downloaded from the following link: [http://acgt.cs.tau.ac.il/multi_omic_benchmark/download.html](http://acgt.cs.tau.ac.il/multi_omic_benchmark/download.html)

## Required R packages
DESeq2, limma, MLSeq, randomForest, clusterProfiler, missMethyl, org.Hs.eg.db, IlluminaHumanMethylation450kanno.ilmn12.hg19, tidyverse, stats, caret, DOSE, enrichplot, ggplot2, ggrepel, pheatmap, ggfortify, ggridges, viridis, hrbrthemes, pathview, reticulate 

## Requiered Python packages
scikit-learn, pandas, seaborn, matplotlib

## Notes
Add raw RNA-seq data (GSM1536837_06_01_15_TCGA_24.tumor_Rsubread_FeatureCounts.txt) and clinical data (clinical) in folder data/raw/.
Add methylation data (methyl) in folder data/raw/breast/.
Filtered data Methylation_data_BRCA_filtered.txt and RNA_FeatureCounts_filtered.txt have to be produced through filtering from raw data and be saved in folder data/filtered/.
Other processed data is fully available in folder data/processed/.
