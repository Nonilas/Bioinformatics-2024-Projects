# Bioinformatics Portfolio with MATLAB

This repository contains a collection of bioinformatics projects completed as part of the DACS Introduction to Bioinformatics course. The projects demonstrate various computational approaches to analyzing biological data using MATLAB.

## 🧬 Skills Showcased

- **Sequence Analysis**: Pairwise alignment, dot plots, significance testing
- **Phylogenetic Analysis**: Multiple sequence alignment, tree construction, evolutionary distance calculation
- **Gene Expression Analysis**: Microarray data processing, differential expression, statistical significance testing
- **Metabolomics**: Principal Component Analysis, data normalization, biomarker identification
- **Data Visualization**: Heatmaps, phylogenetic trees, PCA plots, box plots
- **Statistical Analysis**: T-tests, multiple testing correction, permutation tests

## 🔧 Technologies & Tools

- **MATLAB**: Primary analysis platform - editor
- **Bioinformatics Toolbox**: Key functions including `seqdotplot`, `swalign`, `nwalign`, `getgenpept`
- **Statistics & Machine Learning Toolbox**: PCA analysis, normalization techniques
- **Data Import/Export Tools**: Processing of CSV, Excel, and text files
- **Visualization Packages**: Custom plotting and visualization

## 📂 Project Structure

The repository is organized into the following main directories:

1. **Sequence Alignment Analysis**: Comparative analysis of RING1 protein sequences
2. **Phylogenetic Analysis**: FOXP2 gene evolution across species 
3. **Gene Expression Analysis**: Effect of cigarette and tobacco aerosol exposure on gene expression
4. **Metabolomics**: PCA analysis of metabolites in Parkinson's disease

## 📊 Projects Overview

### 1. Sequence Alignment Analysis

Comparative analysis of RING1 protein sequences between humans, groundhogs, and birds using:

- Dot matrix visualization
- Local and global alignment algorithms
- Statistical significance testing via permutation
- Scoring matrix optimization

**Key Findings**: Discovered significant sequence conservation between mammals, with local alignments revealing functionally important domains.

### 2. Phylogenetic Analysis of FOXP2

Analysis of the FOXP2 gene (associated with language development) across multiple species:

- Multiple sequence alignment of orthologs
- Distance matrix calculation
- Tree construction using various linkage methods
- Evolutionary relationship visualization

**Key Findings**: Demonstrated clear separation between mammalian and non-mammalian lineages, with primates showing closest evolutionary relationships.

### 3. Gene Expression Analysis of Cigarette Exposure

Analysis of differential gene expression in cells exposed to conventional cigarettes vs. carbon heated tobacco products (CHTP):

- Microarray data normalization
- Statistical testing for differential expression
- Multiple testing correction
- Identification of significantly altered genes

**Key Findings**: Identified genes consistently expressed in product-specific patterns and quantified differences between exposure types.

### 4. Metabolomic Analysis of Parkinson's Disease

PCA-based analysis of metabolites in stem cells differentiated into midbrain neuronal precursor cells:

- Data preprocessing and normalization
- Principal Component Analysis
- Identification of key metabolites
- Visualization and interpretation of metabolic differences

**Key Findings**: Identified metabolites that effectively separate Parkinson's disease samples from controls, highlighting potential biomarkers.

## 🚀 Getting Started

### Prerequisites

- MATLAB (R2021a or newer recommended)
- Bioinformatics Toolbox
- Statistics and Machine Learning Toolbox

### Running the Code

1. Clone this repository
2. Open MATLAB and navigate to the repository directory
3. Add all folders to path: `addpath(genpath('.'))`
4. Navigate to a specific project folder
5. Open the corresponding MATLAB Live Script (.mlx) file to see the analysis with explanations
6. Alternatively, run individual .m script files

## 📖 Documentation

Each project directory contains its own README with detailed documentation including:

- Project objectives
- Methodological approaches
- Data processing workflows
- Key findings and biological interpretations
- Technical challenges and solutions

## 🔍 Notable Techniques

- **Sequence Analysis**: 
  - Smith-Waterman local alignment
  - Needleman-Wunsch global alignment
  - BLOSUM scoring matrices
  - Permutation-based significance testing

- **Phylogenetic Analysis**:
  - Distance-based tree construction
  - Multiple linkage methods (single, complete, average)
  - Neighbor-joining algorithm

- **Gene Expression Analysis**:
  - Quantile normalization
  - T-test with multiple testing correction (Benjamini-Hochberg)
  - Volcano plots and heatmaps

- **Metabolomics**:
  - Data imputation for missing values
  - Z-score and mean-centering normalization
  - Principal Component Analysis
  - Feature importance determination

## 👨‍💻 Author

Created by Achilleas Leivadiotis

## 🙏 Acknowledgments

- DACS Introduction to Bioinformatics course
- Original data sources and research studies that provided the datasets
