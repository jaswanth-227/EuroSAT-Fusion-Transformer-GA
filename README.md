## Multi-Scale Feature Fusion and Transformer Encoding for EuroSAT Land Use Classification
## 📄 Conference Paper
[View the Full Paper](EuroSAT_Conference.pdf)

This repository contains the implementation of our research work presented in the ICAIATI Conference.  
The project focuses on **Land Use and Land Cover (LULC) classification using satellite imagery from the EuroSAT dataset**.

The proposed system introduces a hybrid deep learning framework that integrates convolutional neural networks, attention mechanisms, transformer-based contextual modeling, and genetic algorithm–based feature selection to achieve high accuracy classification of satellite images.

---

## Problem Statement

Land Use and Land Cover classification from satellite imagery is essential for many real-world applications such as:

- Environmental monitoring  
- Urban planning  
- Agricultural assessment  
- Climate analysis  

However, accurate classification remains challenging due to:

- Spectral variability in satellite imagery  
- Visual similarity between land cover classes  
- High-dimensional feature representations  
- Complex spatial patterns in remote sensing data  

To address these challenges, this project proposes a **multi-scale hybrid architecture combining CNNs, attention modules, transformers, and evolutionary feature optimization**.

---

## Dataset

The project uses the **EuroSAT dataset**, derived from **Sentinel-2 satellite imagery**.

### Dataset Characteristics

- 27,000 labeled satellite images  
- Image resolution: **64 × 64**  
- 10 land-use classes  

### Classes in the Dataset

- AnnualCrop  
- Forest  
- HerbaceousVegetation  
- Highway  
- Industrial  
- Pasture  
- PermanentCrop  
- Residential  
- River  
- SeaLake  

---

## Proposed Methodology

The proposed framework combines **deep learning and optimization techniques** to improve classification performance.

### Main Components

- Multi-scale feature extraction using **DenseNet-121**  
- Channel and spatial attention mechanisms for feature refinement  
- Adaptive gated fusion to combine multi-level features  
- Transformer encoder to capture long-range spatial dependencies  
- Genetic Algorithm for feature selection and dimensionality reduction  
- Final classification using machine learning models such as:
  - Logistic Regression
  - SVM
  - Random Forest

---

## Pipeline Flow

Input Image  
→ DenseNet-121 Feature Extraction  
→ Attention Blocks  
→ Feature Alignment and Projection  
→ Adaptive Gated Fusion  
→ Transformer Encoder  
→ Global Average Pooling  
→ Feature Concatenation  
→ Genetic Algorithm Feature Selection  
→ Final Classifier  

---

## Experimental Setup

Dataset split used for experiments:

- Training set: **70%**
- Validation set: **15%**
- Test set: **15%**

### Backbone Models Evaluated

- ResNet-50  
- DenseNet-121  
- EfficientNet-B0  
- MobileNet-V2  
- AlexNet  

---

## Results

Performance comparison of models on the EuroSAT dataset:

- ResNet-50 — **95.90%**
- DenseNet-121 — **96.77%**
- EfficientNet-B0 — **95.73%**
- MobileNet-V2 — **93.88%**
- AlexNet — **91.95%**

⭐ **Proposed Fusion + Transformer + Genetic Algorithm Model — 97.36%**

The proposed hybrid model achieves the highest classification accuracy by effectively combining multi-scale feature extraction, attention-based refinement, and contextual modeling.

---

## Key Contributions

- Multi-scale feature extraction using DenseNet architecture  
- Attention-based refinement for improved spatial-spectral representation  
- Transformer-based contextual feature modeling  
- Genetic Algorithm for optimal feature selection  
- Hybrid framework achieving high accuracy on the EuroSAT dataset
