# WBH RNA-seq Analysis

## Project Overview

This project investigates transcriptomic changes induced by Whole-Body Hyperthermia (WBH) treatment in patients with Major Depressive Disorder (MDD) using publicly available RNA-seq data from GEO.

The objective is to reproduce key findings from the original study and gain hands-on experience with RNA-seq differential expression analysis, visualization, and biological interpretation.

---

## Research Question

Does whole-body hyperthermia induce measurable transcriptomic changes in the blood of patients with major depressive disorder?

---

## Dataset

**Source:** GEO (Gene Expression Omnibus)

**Accession:** GSE301868

**Title:**
Whole-blood transcriptomic response to whole-body hyperthermia in participants with major depressive disorder

**Organism:**
Homo sapiens

**Experiment Type:**
Bulk RNA-seq

**Study Design:**

* Sham WBH (control)
* Treatment WBH
* Whole-blood samples collected immediately after intervention

**Samples:**

Samples available in GEO:
- Sham (n = 9)
- Treatment (n = 11)

Note:
The original publication reports that the final differential expression analysis was performed using 18 samples (9 Sham and 9 Treatment) after quality control and sample selection procedures.

**Data Used in This Project:**

* Gene-level expression matrix provided in GEO supplementary files
* No raw FASTQ processing required

---

## Background

Major Depressive Disorder (MDD) is one of the leading causes of disability worldwide.

Whole-Body Hyperthermia (WBH) has been proposed as a potential treatment for depression, but the molecular mechanisms underlying its antidepressant effects remain poorly understood.

The original study reported increased expression of heat-shock proteins and enrichment of immune-related biological pathways following WBH treatment.

---

## Project Objectives

* Learn RNA-seq data analysis workflow
* Explore transcriptomic differences between treatment groups
* Perform differential expression analysis
* Visualize gene expression patterns
* Reproduce findings reported in the original publication
* Build a reproducible bioinformatics portfolio project

---

## Expected Findings

Based on the original publication:

* Upregulation of heat-shock protein genes

  * HSPA1A
  * HSPA1B
  * HSP90AA1
  * HSP90AB1
  * HSPH1

* Enrichment of biological processes related to:

  * Cellular response to heat
  * Protein folding
  * Cytokine signaling
  * Interferon response
  * Immune regulation

---

## Planned Analysis

## Planned Analysis

### 1. Data Preparation
- Inspect GEO supplementary expression matrix
- Create sample metadata table
- Match sample IDs with treatment groups

### 2. Differential Expression Analysis
- Compare Treatment WBH vs Sham WBH
- Identify differentially expressed genes (DEGs)
- Focus on FDR-adjusted q-value < 0.01

### 3. Visualization
- Volcano plot
- Heatmap of selected DEGs
- Expression plots for key heat-shock protein genes

### 4. Gene Set Enrichment Analysis
- Use log-fold changes and p-values from DEG analysis
- Identify enriched biological processes
- Compare findings with the original publication

### 5. Biological Interpretation
- Heat-shock protein response
- Immune response
- Cytokine-related signaling
- Interleukin-6-related pathways

---

## Reference

Original publication:

Whole-blood transcriptomic response to whole-body hyperthermia in participants with major depressive disorder

DOI:
https://doi.org/10.1016/j.bbih.2026.101225


