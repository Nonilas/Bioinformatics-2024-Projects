# Bioinformatics 2024 Projects

Welcome to my collection of **Bioinformatics MATLAB** assignments for the 2024 course: **DACS Introduction to Bioinformatics**. This repository showcases various **sequence analysis**, **gene expression**, **metabolomics**, and **phylogenetic** studies I performed to demonstrate proficiency in **MATLAB** and the **Bioinformatics Toolbox**.

## Table of Contents
1. [Overview](#overview)
2. [Technologies & Toolboxes](#technologies--toolboxes)
3. [Project Folders](#project-folders)
4. [Data Sources](#data-sources)
5. [Usage](#usage)
6. [License](#license)

---

## Overview

These projects span multiple areas of bioinformatics:

- **Sequence Alignment**: Using *local* (Smith-Waterman) vs. *global* (Needleman-Wunsch) alignments to compare protein sequences, assess significance via random permutations, and interpret alignment scoring matrices.
- **Phylogenetics**: Retrieving orthologous sequences (e.g., FOXP2), constructing distance matrices, and building phylogenetic trees (Neighbor-Joining, Hierarchical Clustering).
- **Differential Gene Expression**: Analyzing microarray data (CHTP vs. cigarette exposure), normalizing gene expression, performing statistical tests, and correcting for multiple hypotheses.
- **Metabolomics & PCA**: Comparing healthy vs. sporadic Parkinson’s Disease metabolite profiles. Demonstrating data preprocessing, normalization, PCA loadings, and group separations.
- **Practical Assignments**: Smaller tasks highlighting fundamental MATLAB operations, additional analytics, or course-specific exercises.

---

## Technologies & Toolboxes

- **MATLAB** (R2021a or later recommended)
  - *Bioinformatics Toolbox*: For sequence retrieval (`getgenpept`), alignment (`swalign`, `nwalign`), dot plots (`seqdotplot`), phylogenetic trees (`seqpdist`, `seqlinkage`, `seqneighjoin`), etc.
  - *Statistics and Machine Learning Toolbox*: For PCA, box plots, t-tests, etc.
- **Data Visualization**: Standard MATLAB plotting functions, `gscatter`, `bar`, `heatmap`, `boxplot`.
- **Excel/Spreadsheet I/O**: For reading `Cigarette_exposure.xlsx` or other tabular data (`readtable`).

---

## Project Folders

1. **[1_SequenceAlignment](1_SequenceAlignment)**
   - **SequenceAlignment.m**: Demonstrates `getgenpept`, `seqdotplot`, local (`swalign`) and global (`nwalign`) alignments.
   - **SignificanceTesting.m**: Uses permutation tests (`randperm`) and random sequence generation (`randseq`) to assess alignment score significance.

2. **[2_FOXP2_Phylogenetics](2_FOXP2_Phylogenetics)**
   - **FOXP2_Phylogenetics_Analysis.m**: Retrieves FOXP2 sequences, computes distance matrices (`seqpdist`), builds phylogenetic trees (`seqlinkage`, `seqneighjoin`), and visualizes them.

3. **[3_CigaretteExposure_Expression](3_CigaretteExposure_Expression)**
   - **CigaretteExposure_Analysis.m**: Reads gene expression data from `Cigarette_exposure.xlsx`.
   - **DifferentialExpression.m**: Performs normalization (quantile, median fold-change, Z-score), t-tests, BH FDR correction, and histogram visualizations.

4. **[4_Parkinsons_Metabolomics_PCA](4_Parkinsons_Metabolomics_PCA)**
   - **Parkinsons_PCA_Analysis.m**: Analyzes metabolomics data from healthy vs. sporadic PD groups. Includes missing data imputation, PCA, loadings extraction, and box plots.
   - **Normalization_Comparison.m**: Compares mean-centering vs. Z-score scaling and demonstrates the effect on PCA results.

5. **[5_MCF_Hypoxia_Expression](5_MCF_Hypoxia_Expression)**
   - **MCF_Hypoxia_RawExpression_Analysis.m**: Processes raw microarray/RNA-seq data under hypoxia, performs normalization, and identifies differentially expressed genes.

6. **[6_PCA_Final_Assignment](6_PCA_Final_Assignment)**
   - **PCA_Assignment.m**: Final consolidated PCA project, exploring advanced PCA features, scree plots, and loadings with multiple datasets.

7. **[Additional_Practicals](Additional_Practicals)**
   - Contains smaller scripts like `practical3_2023.m`, `practical5_2023.m`, `practical6_2024.m`, demonstrating fundamental MATLAB/bioinformatics tasks.

8. **[Utilities](Utilities)**
   - **HelperFunctions.m**: Shared functions for plotting, statistics, or repeated tasks.

---

## Data Sources

- **NCBI GenBank** for protein sequences (e.g., RING1, FOXP2).
- **EBI ArrayExpress / Local Excel Files** for microarray gene expression data (`Cigarette_exposure.xlsx`).
- **Local Metabolomics Data** (`parkinsons_metabolites.txt`).

> **Note**: Some data files (Excel, text) may not be included in this repo for size or licensing reasons. Adjust file paths as needed if you place them in the same folder.

---

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/Bioinformatics_2024_Projects.git
