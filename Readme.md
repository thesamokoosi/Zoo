# 🐋 Phylogenetic Analysis of the Blue Whale (*Balaenoptera musculus*)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Data Science](https://img.shields.io/badge/Data_Science-Statistics-orange?style=for-the-badge)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Phylogenetics-green?style=for-the-badge)

## 👨‍💻 Author
**Samuel Olanrewaju Okoosi**  
*Department of Statistics, University of Ibadan*

---

## 📖 Project Overview
This repository contains a computational analysis of the evolutionary history of the Blue Whale (*Balaenoptera musculus*). Using the **Mitochondrial Cytochrome c Oxidase subunit 1 (COX1)** protein sequence as a molecular marker, this project applies statistical and bioinformatic techniques to determine genetic relationships between cetaceans and terrestrial artiodactyls.

The analysis processes raw sequence difference data to reconstruct phylogenetic trees, calculate percentage identities, and estimate evolutionary divergence times based on molecular clock hypotheses.

## 📂 Files in Repository
*   `adenikezoo.ipynb`: The primary Jupyter Notebook containing the raw data compilation, statistical calculations, and code for all five visualizations.

## 🛠️ Methodology
The analysis is conducted using **Python** and relies on the following statistical approaches:
1.  **Data Compilation:** Construction of a dataset comprising 30 species based on BLAST alignment results.
2.  **Genetic Distance Calculation:** Computing the raw amino acid differences (mutations) between the Blue Whale and related species.
3.  **Molecular Clock Estimation:** Using a calibrated mutation rate ($\approx 0.0971$ changes/MYA) to estimate the divergence time in Millions of Years Ago (MYA).
4.  **Hierarchical Clustering:** Application of **Ward’s Linkage Method** to generate a phylogenetic dendrogram, grouping species into clades based on genetic similarity.

## 📊 Visualizations Generated
The notebook (`adenikezoo.ipynb`) generates five high-quality figures to interpret the data:
1.  **Complete Evolutionary Analysis Table:** A summary of taxonomy, identity percentages, and mutation counts.
2.  **Percentage Similarity Chart:** A zoomed-in bar chart (94%–100%) highlighting the conservation of the COX1 gene within the family *Balaenopteridae*.
3.  **Evolutionary Distance Chart:** A bar chart visualizing the raw count of amino acid mutations, showing the "steps" of evolution from Rorquals to Artiodactyls.
4.  **Divergence Time Lollipop Chart:** A timeline ranking species by their estimated split from the Blue Whale lineage.
5.  **Phylogenetic Dendrogram:** A tree diagram illustrating the clustering of Rorquals, Odontocetes (toothed whales), and the Hippopotamus as the closest terrestrial relative.

## 🚀 How to Run
To replicate this analysis, ensure you have Python installed along with the required libraries.

### Prerequisites
```bash
pip install pandas matplotlib seaborn scipy numpy
