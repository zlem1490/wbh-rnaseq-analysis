# WBH RNA-seq Analysis

## Project Overview

This project aims to analyze transcriptomic changes induced by Whole-Body Hyperthermia (WBH) treatment in patients with Major Depressive Disorder (MDD) using publicly available RNA-seq data.

The goal is to reproduce and understand a complete RNA-seq analysis workflow, from raw sequencing data processing to differential gene expression analysis and biological interpretation.

---

## Dataset

**Source:** GEO (Gene Expression Omnibus)

**Title:**
Whole-blood transcriptomic response to whole-body hyperthermia in participants with major depressive disorder

**Organism:**
Homo sapiens

**Experiment Type:**
Bulk RNA-seq (Expression profiling by high throughput sequencing)

**Study Design:**

* Sham WBH group (control)
* Treatment WBH group
* Whole-blood samples collected immediately after intervention

**Samples Used for Pilot Analysis:**
GSE301868

* GSM9091007 (Sham, Female)
* GSM9091013 (Sham, Male)
* GSM9091022 (Treatment, Female)
* GSM9091025 (Treatment, Male)

---

## Reference

Original study:

Whole-blood transcriptomic response to whole-body hyperthermia in participants with major depressive disorder

Published: 2026

DOI:
https://doi.org/10.1080/17435889.2025.2572991

---

## Project Objectives

* Understand the RNA-seq analysis pipeline
* Process raw FASTQ files
* Perform quality control (QC)
* Generate gene-level count matrices
* Explore transcriptomic differences between treatment conditions
* Build a reproducible bioinformatics workflow
* Document the analysis process on GitHub

---

## Planned Workflow

### 1. Data Acquisition

* Download FASTQ files from GEO
* Organize metadata

### 2. Quality Control

* FastQC

### 3. Read Alignment

* Alignment to human reference genome

### 4. Gene Quantification

* Generate count matrix

### 5. Differential Expression Analysis

* DESeq2

### 6. Visualization

* PCA
* Volcano Plot
* Heatmap

### 7. Biological Interpretation

* Differentially expressed genes (DEGs)
* Heat shock protein genes
* Immune and inflammatory pathways

---
## Notes

This repository is intended as a learning and portfolio project focused on gaining hands-on experience with bulk RNA-seq data analysis and reproducible bioinformatics workflows.
