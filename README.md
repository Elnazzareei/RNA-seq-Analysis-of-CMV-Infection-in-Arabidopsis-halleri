# Project Overview
This project analyzes RNA-seq data to investigate the interaction between Cucumber Mosaic Virus (CMV) and its natural host Arabidopsis halleri under different environmental conditions.
The dataset is obtained from the GEO database.
Dataset: GSE197739
The goal of the study is to explore how CMV infection affects the transcriptome of A. halleri, particularly under zinc-excess conditions that simulate heavy-metal environments in the plant’s natural habitat.

# Biological Background
Arabidopsis halleri is a pseudometallophyte plant species that naturally grows in environments with high heavy-metal concentrations.
Interestingly, this plant is frequently infected with Cucumber Mosaic Virus (CMV) in the wild. Instead of behaving strictly as a pathogen, CMV may establish a mutualistic interaction with its host.
Experimental observations suggest that:
-Under low heavy-metal conditions, CMV infection causes growth retardation but improves drought tolerance.
-Under high heavy-metal conditions, CMV infection does not cause visible symptoms and provides mild drought tolerance.
Transcriptomic analysis suggests that CMV may be recognized as a symbiont rather than a pathogen by its host plant.

# Experimental Design
RNA-seq was performed on leaf samples of Arabidopsis halleri across four conditions.
Condition, Description,	Replicates:
Mock, CMV-free plants,	3
CMV,	CMV-infected plants,	3
Zn_Mock,	CMV-free plants under zinc excess,	3
Zn_CMV,	CMV-infected plants under zinc excess,	3
Total samples: 12 RNA-seq libraries

# Analysis Workflow
The RNA-seq analysis pipeline includes the following steps:
1-Downloading RNA-seq dataset from the GEO database (GSE197739).
2-Loading gene count files
3-Merging gene count datasets
4-Creating sample metadata
5-Data normalization
6-Exploratory Data Analysis
7-Differential Gene Expression Analysis
8-Visualization: PCA plots, Volcano plots, Heatmaps of top differentially expressed genes

# Tools Used
Python,
pandas,
numpy,
matplotlib,
seaborn,
scipy,
scikit-learn,
statsmodels
