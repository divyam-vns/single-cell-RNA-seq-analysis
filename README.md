# scRNA-seq Analysis (Seurat & Scanpy)

This repository contains beginner-friendly, fully annotated
single-cell RNA-seq pipelines implemented in:

- R (Seurat)
- Python (Scanpy)

## Features
- Quality control
- Normalization
- Highly variable gene selection
- PCA
- Clustering
- UMAP visualization

## Input
10x Genomics filtered_feature_bc_matrix format.

## Output
Processed Seurat (.rds) and Scanpy (.h5ad) objects.


# Single-Cell RNA-seq Analysis Pipeline (Seurat & Scanpy)

**Author:** Dr. Divya Mishra, Ph.D.  
**Expertise:** Molecular Genetics, Clinical Genomics, NGS Data Analysis  

---

##  Overview

This repository contains an **end-to-end single-cell RNA sequencing (scRNA-seq) analysis pipeline** implemented using **widely adopted, standard tools** in:

- **R (Seurat)**
- **Python (Scanpy)**

The workflows demonstrate applied expertise in **NGS data analysis**, from raw data processing to biological interpretation, without developing custom models.

---

## Analysis Scope

The pipeline includes:

- Quality control and filtering
- Normalization and scaling
- Dimensionality reduction (PCA, UMAP)
- Clustering (Louvain / Leiden)
- Marker-based cell type annotation
- Differential gene expression analysis
- Multi-sample / multi-batch integration
- Pathway enrichment analysis (GSEA)
- Publication-quality figures
- Automated Markdown / PDF reporting


---

## R Workflow (Seurat)

- QC metrics (nFeature_RNA, nCount_RNA, mitochondrial content)
- Normalization and feature selection
- PCA, UMAP visualization
- Graph-based clustering
- Marker gene identification
- Manual cell type annotation using known markers
- Differential expression analysis
- Multi-sample integration
- GSEA using `clusterProfiler`
- R Markdown reporting

---

## Python Workflow (Scanpy)

- AnnData-based preprocessing
- Normalization and log transformation
- PCA, neighbors, UMAP
- Leiden clustering
- Differential expression testing
- Cell type annotation
- Multi-sample integration
- Pathway enrichment using `gseapy`
- Markdown reporting

---

## Outputs

The pipeline generates:

- UMAP plots (clusters, batches, cell types)
- Feature plots for marker genes
- Differential expression tables
- Pathway enrichment results
- Reproducible analysis reports

All outputs are saved in the `results/` directory.

---

## Software Requirements

### R Packages
- Seurat
- clusterProfiler
- org.Hs.eg.db
- enrichplot
- ggplot2

### Python Packages
- scanpy
- anndata
- pandas
- numpy
- matplotlib
- gseapy

---
