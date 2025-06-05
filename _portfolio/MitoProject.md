---
title: "Mito Project"
excerpt: "ML Classifier to identify mitochondria gene expression changes in scRNA-seq data <br/><img src="/images/Mito.png" alt="Mito Project Image" />"
collection: portfolio
---

# 🧬 MITOPROJECT — A Machine Learning Pipeline for Mitochondrial Dysregulation in Single Cells

**Summary**  
MITOPROJECT is a bioinformatics pipeline designed to identify mitochondrial gene expression changes in single-cell RNA-seq data under inflammatory conditions. Using a combination of R-based preprocessing, machine learning classification in Python, and Gene Ontology (GO) enrichment analysis, this project uncovers mitochondrial dysfunction signatures in LPS-treated peripheral blood mononuclear cells (PBMCs).

---

## 🎯 Key Objectives

- Preprocess scRNA-seq data to extract nuclear- and mitochondrial-encoded gene expression profiles  
- Train ML models to classify LPS-treated vs. control conditions based on mitochondrial gene expression  
- Identify top contributing genes and investigate their biological functions through GO enrichment  

---

## 🧬 Dataset

- **GEO Accession**: [GSE226488](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE226488)  
- **PMID**: [37414801](https://pubmed.ncbi.nlm.nih.gov/37414801)

---

## 🧰 Technologies Used

- **R**: Seurat, dplyr (Data Preprocessing & GO Analysis)  
- **Python**: scikit-learn, pandas, matplotlib (Machine Learning)  

---

## 🔁 Pipeline Overview

1. **Preprocessing**  
   Extract mitochondrial gene expression from Seurat objects using curated gene lists (MitoCarta3.0)

2. **Classification**  
   Train classifiers (e.g., Random Forest, Logistic Regression) to differentiate between treated and control cells

3. **Biological Interpretation**  
   Perform GO enrichment on top-ranked genes to reveal mitochondrial pathways affected by inflammation

---

## ✅ Outcome

This project demonstrates how integrated multi-language pipelines can be used to explore mitochondrial-nuclear communication in inflammation. The code is modular, reproducible, and designed to be run as an interactive app through Streamlit.

---

## 🔗 Links

- 📁 [View Code on GitHub](https://github.com/RpN1107/MitoProject)
- 📝 [View Report](https://github.com/RpN1107/MitoProject/blob/d3f117476b4edb2249d7958822e922494a0bed3b/Report.pdf)

---

*Developed by Rithwik Nambiar*
