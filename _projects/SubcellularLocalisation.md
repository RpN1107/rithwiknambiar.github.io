---
title: "Subcellular Protein Localisation Predictor"
excerpt: "Predict the subcellular localisation of proteins from amino acid sequences"
image: "/images/Projects/DL_logo.png"
bg_image: "/images/Projects/DL.png"
collection: projects
permalink: /projects/sub-loc-pred/
---
----------------------------------

# 🧬 Subcellular Protein Localisation Predictor

A deep learning-based tool to predict the **subcellular localisation** of human proteins using only their amino acid sequences. Understanding where a protein localises within a cell is critical for studying its function and role in cellular pathways.

---

## 🔍 Overview

This tool allows users to input protein sequences and obtain predictions for **nucleus, cytoplasm, membrane, secretory pathway**, and more. Predictions are powered by **ESM2 embeddings**, a transformer-based protein language model trained on millions of sequences.

The project includes:

* Preprocessing of protein sequences
* Generation of embeddings using ESM2
* Training a multi-label neural network classifier
* A **Streamlit web app** for real-time predictions

---

## 🧠 Key Features

* **Deep Learning Embeddings**: Extracts meaningful sequence features using `facebook/esm2_t6_8M_UR50D`.
* **Multi-Label Classification**: Predicts multiple subcellular compartments per protein.
* **Performance Benchmarked**: Model evaluated for speed, memory, and classification accuracy.
* **Interactive Web App**: Upload FASTA sequences, view probabilities and binary predictions, and download CSV results.

---

## 🧪 Methodology

1. **Data Collection**: Human protein sequences and annotations downloaded from [UniProt](https://www.uniprot.org/).
2. **Preprocessing**: Sequences cleaned, formatted, and split for training and validation.
3. **Embedding Generation**: Protein sequences converted into numerical embeddings using ESM2.
4. **Model Training**: Multi-label classifier trained on embeddings with careful handling of class imbalance.
5. **Evaluation**: Metrics such as F1-score, AUROC, and precision-recall curves computed.

---

## 📈 Results

* **High Accuracy**: Model performs well across multiple subcellular compartments.
* **UMAP Visualization**: Embeddings cluster according to localisation class.
* **Real-Time Predictions**: Streamlit app allows interactive exploration and CSV export.

---

## 🚀 Try It

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/protein_localisation_app.git
cd protein_localisation_app
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 📂 Links

* 📁 [GitHub Repository](https://github.com/RpN1107/Subcellular-Localisation-Predictor)
* 📝 [Project Report (PDF)](https://github.com/RpN1107/Subcellular-Localisation-Predictor/blob/main/notebooks/Report.pdf)

---

*Developed by Rithwik Nambiar*
