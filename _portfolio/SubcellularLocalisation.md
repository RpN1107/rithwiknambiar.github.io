---
title: "Subcellular Protein Localisation Predictor"
excerpt: "ML model to predict the subcellular localisation of proteins from their amino acid sequence
image: /images/Mito.png
collection: portfolio
permalink: /portfolio/
---

# 🧬 Subcellular Localisation Predictor

Predicting the destination of proteins within a cell is critical for understanding their function and role in cellular pathways. This project leverages transformer-based language models trained on protein sequences to predict the **subcellular localisation** of human proteins using only their amino acid sequences.

---

## 🔍 Overview

This tool allows users to input protein sequences and obtain predictions on where within a eukaryotic cell the protein is most likely to localise — such as the **nucleus**, **cytoplasm**, **membrane**, or **secretory pathway**. The predictions are powered by embeddings from **ESM2**, a deep learning model trained on millions of protein sequences.

---

## 🧠 Key Features

- **Deep Learning Embeddings**: Uses the `facebook/esm2_t6_8M_UR50D` protein language model to extract meaningful features from sequences.
- **Classifier Performance**: Models were benchmarked for speed, memory, and accuracy. ESM2 outperformed others in overall performance.
- **Web App**: A user-friendly Streamlit interface allows interactive sequence input and visualisation of prediction probabilities.

---

## 🧪 Methodology

1. **Data Source**: Reviewed human proteins were downloaded from [UniProt](https://www.uniprot.org/).
2. **Preprocessing**: Sequences and their subcellular annotations were cleaned and formatted.
3. **Embedding Comparison**: Three embedders were evaluated on a stratified sample for efficiency and embedding quality.
4. **Classifier Training**: A final classifier was trained using ESM2 embeddings on the full dataset.

---

## 📈 Results

- The classifier achieves high accuracy across multiple localisation classes.
- Visualisation using UMAP of embeddings shows clustering by localisation class.
- The Streamlit app enables real-time prediction and exploration.

---

## 🚀 Try It

You can run the app locally:

```bash
streamlit run app.py
```

## Links

- 📁 [View Code on GitHub](https://github.com/RpN1107/Subcellular-Localisation-Predictor)
- 📝 [View Report](https://github.com/RpN1107/Subcellular-Localisation-Predictor/blob/7b8c21767b5c01bf100e1ca829896f615c24ad2e/Report.pdf)
---

*Developed by Rithwik Nambiar*
