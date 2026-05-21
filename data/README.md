# Data description

This folder contains processed Seurat objects used for hematopoiesis
single-cell RNA-seq analysis.

## Files

### hemato_preprocessed_nonlinred.rds
Seurat object after:
- quality control filtering
- normalization (LogNormalize)
- variable feature selection
- scaling
- PCA dimensional reduction
- graph-based clustering
- UMAP embedding

This object is used as input for downstream clustering visualization
and marker gene analysis.

### hemato_annotated.rds
Annotated Seurat object containing manually assigned cell identities
based on marker gene expression.

## Raw data
Raw sequencing data are not included in this repository due to file size constraints. Datasets were provided as part of a collaborative hematopoietic single-cell RNA-seq analysis project and included multiple experimental datasets used for pipeline development and comparative analysis.

## Software
Objects were generated using:
- Seurat (v5)
- R (v4.x)
