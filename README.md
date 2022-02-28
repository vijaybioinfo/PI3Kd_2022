Intermittent PI3Kδ inhibition sustains anti-tumor immunity and minimizes toxicity
------------

This repository contains the scripts used to analyze our samples from treatment of PI3Kδi AMG319 in patients with resectable head and neck cancer in a neoadjuvant, double-blind, placebo-controlled randomised phase-II trial.
The data contains single-cell Smart-seq2 and 10x samples.

REQUIREMENTS
------------

This project requires the following modules/programs:

* TopHat (v1.4.1)
* HTSeq (v0.7.1)
* Cutadapt (v1.3)
* [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html) (v.1.14.1)
* fastcluster (v.1.1.25)
* dendextend (v.1.7.0)
* [Cell Ranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger) (v2.0.2)
* [Seurat](https://satijalab.org/seurat) (v2.1)
* [MAST](https://www.bioconductor.org/packages/release/bioc/html/MAST.html) (1.8.2)

INSTALLATION
------------

* You can follow the instructions for [our mapping pipeline](https://github.com/vijaybioinfo/cellranger_wrappeR) using Cell Ranger.
* For the single-cell quality control just pull [our in-house script](https://github.com/vijaybioinfo/quality_control).
* Clustering of single-cell data with [our pipeline](https://github.com/vijaybioinfo/clustering) using Seurat.
* You can pull our [in-house pipeline](https://github.com/ndu-UCSD/LJI_RNA_SEQ_PIPELINE_V2) for mapping bulk data.

Global description
------------

*Demultiplexing libraries*: Cell Ranger was used to demultiplex the 10x libraries. And our in-house
mapping [pipeline](https://github.com/ndu-UCSD/LJI_RNA_SEQ_PIPELINE_V2) was used for the bulk data.

*Quality control*: An in-house [script](https://github.com/vijaybioinfo/quality_control)
was used to explore the quality of the data and select the thresholds.

*Clustering*: Seurat was used to cluster the data.

For more specific information about the data generation and processing, please check the methods.

MAINTAINERS
-----------

Current maintainers:
* Ciro Ramírez-Suástegui (ksuasteguic@gmail.com, ciro@lji.org)

Contact
-----------
Please email Ciro Ramírez-Suástegui (ciro@lji.org) and Vijayanand Pandurangan (vijay@lji.org).
