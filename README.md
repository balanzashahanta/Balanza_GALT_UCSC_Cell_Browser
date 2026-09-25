# From Genome to Cell: Exploring GALT Using the UCSC Cell Browser

**Name:** Shahanta Dawn B. Balanza  
**Assigned Gene:** GALT  
**Associated Disease:** Classic Galactosemia  
**Date:** September 25, 2026

## UCSC Cell Browser Activity

This activity investigates the expression of the human **GALT** gene at the single-cell level using the **UCSC Cell Browser**. The activity focuses on exploring a relevant human tissue dataset, examining cell clusters and cell types, visualizing GALT expression, and comparing its expression with marker genes.

## 1. Assigned Gene and Disease

The assigned gene is **GALT (galactose-1-phosphate uridylyltransferase)**, and the associated disease is **Classic Galactosemia**.

The GALT gene is relevant to this activity because pathogenic variants in GALT are associated with classic galactosemia, a disorder affecting the body's ability to properly metabolize galactose.

## 2. Organ/Tissue Choice and Dataset Information

### Relevant Organ/Tissue

The liver was selected because the GALT gene encodes galactose-1-phosphate uridylyltransferase, an enzyme involved in galactose metabolism. Classic galactosemia can significantly affect liver function, making the liver a relevant tissue for examining GALT expression.

### Selected Dataset

**Dataset Name:** Human Liver Cell Atlas - Hepatocyte Cells

**Organ/Tissue:** Human liver

**Organism:** Homo sapiens

**Cell Type:** Hepatocytes

**Number of Cells:** 228,368 cells

**Publication/Study:** Speir et al. (2021)

**Dataset URL:** https://human-liver-cell-atlas.cells.ucsc.edu

### Why This Dataset Was Selected

The Human Liver Cell Atlas - Hepatocyte Cells dataset was selected because the liver is directly relevant to galactose metabolism and the clinical effects of classic galactosemia. The dataset contains human hepatocyte cells, allowing the expression of GALT to be examined across different hepatocyte cell populations.

## 3. Understanding the Cell Map

### Visualization Type

The dataset is displayed using a **UMAP (Uniform Manifold Approximation and Projection)** visualization. UMAP reduces high-dimensional single-cell expression data into a two-dimensional map so that cells with more similar molecular profiles are generally positioned closer together.

### Meaning of Each Dot

Each dot represents one measured **hepatocyte cell** in the dataset. The dataset contains approximately **228,368 cells**.

### Meaning of the Clusters

The clusters represent different **hepatocyte cell populations or subtypes** identified in the Human Liver Cell Atlas dataset. Cells within the same cluster have similar overall molecular profiles, while the different clusters represent distinct annotated hepatocyte populations.

### Visible Cell-Type/Cluster Labels

At least three visible labels are:

- **Periportal Hepatocyte**
- **Pericentral Hepatocyte**
- **Ribosomal+ Hepatocyte**

Other visible labels include **Mito+ Hepatocyte, UGT+ Hepatocyte, SERPINE1+ Hepatocyte,** and **Cycling**.

### Important Note

The UMAP axes do not represent physical locations in the liver. The positions of cells are based on similarities in their molecular profiles rather than their anatomical positions in the body.

## 4. Assigned Gene Expression

### Gene Searched

**Gene Symbol:** GALT

**Dataset:** Human Liver Cell Atlas - Hepatocyte Cells

### Expression Pattern

GALT expression was **low or undetected in most cells** in the dataset. The expression legend showed that 93.8% of cells had an expression value of 0, while 5.7% had a value of 1 and 0.5% had a value of 2. Only a very small fraction of cells showed higher expression values.

### Clusters with Detectable Expression

GALT expression was detectable in scattered cells across the hepatocyte map, but there was **no clearly dominant hepatocyte cluster showing strong GALT expression**. The overall expression pattern was low across the different hepatocyte populations.

### Clusters with Little or No Detectable Expression

Most of the visible hepatocyte clusters showed little or no detectable GALT expression, including **Periportal Hepatocyte, Pericentral Hepatocyte, Ribosomal+ Hepatocyte, Mito+ Hepatocyte, UGT+ Hepatocyte,** and **SERPINE1+ Hepatocyte**.

### Interpretation

In this dataset, GALT expression appears to be low or undetected in most measured hepatocytes. This result should be interpreted as the expression pattern observed in this particular single-cell dataset and does not mean that GALT is completely absent from hepatocytes or from liver tissue.
