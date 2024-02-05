# Koupourtidou-Schwarz-et-al

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10619836.svg)](https://doi.org/10.5281/zenodo.10619836)

Spatial and single cell transcriptomics of all cells in the mouse cerebral cortex in response to brain injury.
This repository contains the code for analyzing single-cell (scRNA-seq) and spatial transcriptomics (stRNA-seq) data from: Koupourtidou-Schwarz-et-al

# Data

Both FASTQ and Cell/Space Ranger-generated matrix files generated in this project can be directly downloaded from GEO: [GSE226211](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE226208) 

# Code

To run the case study, several packages must be installed. As both R and python packages are required, we prefer using a conda environment. To facilitate the setup of a conda environment, we have provided the environment_scRNAseq.yml (single cell analysis) and  environment_stRNAseq.yml (spatial analysis) files, which contains all conda and pip installable dependencies.
