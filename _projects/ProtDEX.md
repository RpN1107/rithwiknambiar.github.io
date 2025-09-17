---
title: "ProtDEX"
excerpt: "An interactive Shiny app for differential protein expression analysis in proteomics data"
image: "/images/Projects/ProtDEX.png"
bg_image: "/images/Projects/ProtDEX.png"
collection: projects
permalink: /projects/protdex/
---

# 🧬 ProtDEX: A Shiny App for Differential Protein Expression

**Summary**  
ProtDEX is an interactive bioinformatics tool built in **R Shiny** to perform **differential protein expression analysis** from proteomics datasets. The app integrates **preprocessing, normalization, visualization, and statistical testing** into an easy-to-use interface, making proteomics workflows accessible for both computational and experimental biologists.  

---

## 🎯 Key Objectives

- Simplify the analysis of proteomics data through an intuitive web interface  
- Provide flexible **normalization** and **filtering** options for raw protein intensities  
- Enable **differential expression analysis** between experimental groups  
- Offer rich **visualization tools** (heatmaps, volcano plots, PCA) for data interpretation  

---

## 🧬 Dataset Support

- Accepts **CSV** and **Excel** input formats  
- Tested with **label-free quantification (LFQ)** proteomics datasets  
- Includes a **test dataset** in the `tests/` folder for demo and reproducibility  

---

## 🧰 Technologies Used

- **R Shiny** (Interactive App Framework)  
- **tidyr, dplyr** (Data Preprocessing)  
- **preprocessCore** (Normalization)  
- **ggplot2, ggrepel, pheatmap** (Visualization)  
- **DT** (Interactive Data Tables)  

---

## 🔁 Workflow Overview

1. **Data Import & QC**  
   Upload raw intensity data, check missing values, and remove contaminants  

2. **Normalization**  
   Apply quantile normalization or user-selected methods  

3. **Differential Expression Analysis**  
   Compare experimental groups to identify up/down-regulated proteins  

4. **Visualization**  
   Generate PCA plots, volcano plots, heatmaps, and export results  

---

## ✅ Outcome

ProtDEX streamlines proteomics analysis into a single pipeline, removing the need for extensive coding. The app is designed to help biologists and bioinformaticians quickly detect differentially expressed proteins and visualize results interactively.  

---

## 🔗 Links

- 📁 [View Code on GitHub](https://github.com/RpN1107/ProtDEX_ShinyApp)  
- 🧪 [Test Dataset](/TestData/Test.csv)  

---

*Developed by Rithwik Nambiar*
