# Multi-Scale Feature Fusion and Transformer Encoding for EuroSAT Land Use Classification

📄 Conference Paper:  
[View the Full Paper](EuroSAT_Conference.pdf)

📂 Dataset:  
https://www.kaggle.com/datasets/raoofnaushad/eurosat-sentinel2-dataset

---

## Overview

This repository contains the implementation of our research work presented in the ICAIATI Conference.

The project focuses on **Land Use and Land Cover (LULC) classification using satellite imagery from the EuroSAT dataset**.

The proposed system introduces a **hybrid deep learning framework** that integrates:

- Convolutional Neural Networks (CNNs)
- Attention Mechanisms
- Transformer-based Contextual Modeling
- Genetic Algorithm-based Feature Selection

This hybrid architecture improves classification performance and achieves high accuracy in satellite image classification.

---

## Problem Statement

Land Use and Land Cover (LULC) classification from satellite imagery is essential for many real-world applications such as:

- Environmental Monitoring
- Urban Planning
- Agricultural Assessment
- Climate Analysis

However, accurate classification remains challenging due to:

- Spectral variability in satellite imagery
- Visual similarity between land cover classes
- High-dimensional feature representations
- Complex spatial patterns in remote sensing data

To address these challenges, this project proposes a **multi-scale hybrid architecture combining CNNs, attention modules, transformers, and evolutionary feature optimization.**

---

## Dataset

This project uses the **EuroSAT dataset**, derived from **Sentinel-2 satellite imagery**.

Dataset Link:  
https://www.kaggle.com/datasets/raoofnaushad/eurosat-sentinel2-dataset

### Dataset Characteristics

- Total Images: **27,000**
- Image Resolution: **64 × 64**
- Number of Classes: **10**

### Land Use Classes

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

After downloading the dataset, place it in the following directory:

dataset/
└── EuroSAT/

---

## Proposed Methodology

The proposed framework combines **deep learning and optimization techniques** to improve classification performance.

### Main Components

- Multi-scale feature extraction using **DenseNet-121**
- Channel and Spatial Attention mechanisms for feature refinement
- Adaptive Gated Fusion to combine multi-level features
- Transformer Encoder to capture long-range spatial dependencies
- Genetic Algorithm for feature selection and dimensionality reduction
- Final classification using machine learning models such as:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest

---

## Pipeline Flow

Input Image  
↓  
DenseNet-121 Feature Extraction  
↓  
Attention Blocks  
↓  
Feature Alignment and Projection  
↓  
Adaptive Gated Fusion  
↓  
Transformer Encoder  
↓  
Global Average Pooling  
↓  
Feature Concatenation  
↓  
Genetic Algorithm Feature Selection  
↓  
Final Classifier  

---

## Experimental Setup

Dataset split used for experiments:

- Training Set — **70%**
- Validation Set — **15%**
- Test Set — **15%**

### Backbone Models Evaluated

- ResNet-50
- DenseNet-121
- EfficientNet-B0
- MobileNet-V2
- AlexNet

---

## Results

Performance comparison of models on the EuroSAT dataset:

| Model | Accuracy |
|------|------|
| ResNet-50 | 95.90% |
| DenseNet-121 | 96.77% |
| EfficientNet-B0 | 95.73% |
| MobileNet-V2 | 93.88% |
| AlexNet | 91.95% |
| ⭐ Proposed Hybrid Model | **97.36%** |

The proposed **Fusion + Transformer + Genetic Algorithm framework** achieves the highest classification accuracy by effectively combining multi-scale feature extraction, attention-based refinement, and contextual modeling.

---

## Key Contributions

- Multi-scale feature extraction using DenseNet architecture
- Attention-based refinement for improved spatial–spectral representation
- Transformer-based contextual feature modeling
- Genetic Algorithm for optimal feature selection
- Hybrid framework achieving **97.36% accuracy** on the EuroSAT dataset

