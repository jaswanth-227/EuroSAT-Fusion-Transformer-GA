# 🌍 Multi-Scale Feature Fusion & Transformer Encoding for EuroSAT Land Use Classification

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3500&pause=1000&color=00C4FF&center=true&vCenter=true&width=900&lines=Multi-Scale+Feature+Fusion+%26+Transformer+Encoding;EuroSAT+Land+Use+Classification;Best+Paper+Award+%7C+ICAIATI+2025;Taylor+%26+Francis+Publication" />
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge&logo=pytorch)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Research](https://img.shields.io/badge/Conference-ICAIATI%202025-success?style=for-the-badge)
![Publication](https://img.shields.io/badge/Publication-Taylor%20%26%20Francis-blueviolet?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Test%20Accuracy-97.36%25-brightgreen?style=for-the-badge)

</p>

<p align="center">

📄 **Conference Paper:** [EuroSAT_Conference.pdf](EuroSAT_Conference.pdf)

📂 **Dataset:** https://www.kaggle.com/datasets/raoofnaushad/eurosat-sentinel2-dataset

🏆 **Best Paper Award – ICAIATI 2025**

</p>

---

# 📖 Overview

This repository contains the official implementation of our **award-winning research** on **Land Use and Land Cover (LULC) Classification** using satellite imagery from the **EuroSAT** benchmark dataset.

The proposed framework introduces a **Multi-Level Feature Fusion Transformer (MLFT)** architecture that combines convolutional feature extraction, attention mechanisms, transformer-based contextual modeling, and genetic algorithm optimization to significantly improve classification performance.

Our proposed approach achieved **97.36% Test Accuracy**, outperforming several state-of-the-art CNN architectures.

---

# ✨ Highlights

- 🥇 **Best Paper Award – ICAIATI 2025**
- 📄 Accepted for publication in **Taylor & Francis**
- 🚀 **97.36% Test Accuracy**
- 🛰️ Multi-Level Feature Fusion Framework
- 🎯 Channel & Spatial Attention
- 🤖 Transformer-based Global Context Learning
- 🧬 Genetic Algorithm Feature Selection
- 🌍 Evaluated on the EuroSAT Benchmark Dataset

---

# 🎯 Applications

The proposed framework can be applied in:

- 🌾 Precision Agriculture
- 🌍 Environmental Monitoring
- 🏙 Urban Planning
- 🌲 Forest Monitoring
- 🌊 Water Resource Mapping
- 🚨 Disaster Management
- 🛰 Remote Sensing Analytics

---

# 📂 Dataset

This work uses the **EuroSAT RGB Dataset**, derived from **Sentinel-2 satellite imagery**.

| Attribute | Value |
|-----------|-------|
| Dataset | EuroSAT RGB |
| Images | 27,000 |
| Classes | 10 |
| Resolution | 64 × 64 |
| Satellite | Sentinel-2 |

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

---

# 🏗️ Proposed Architecture

The proposed **MLFT architecture** integrates CNN-based feature extraction with attention mechanisms, transformer encoding, and evolutionary optimization.

<p align="center">
<img src="images/architecture.png" width="1000">
</p>

<p align="center">
<b>Figure.</b> Overall architecture of the proposed Multi-Level Feature Fusion Transformer (MLFT).
</p>

---

# ⚙️ Methodology

```text
Satellite Image
        │
        ▼
DenseNet-121
Multi-Level Feature Extraction
        │
        ▼
Channel Attention Block
        │
        ▼
Spatial Attention Block
        │
        ▼
Feature Alignment
        │
        ▼
Adaptive Gated Fusion
        │
        ▼
Transformer Encoder
        │
        ▼
Global Average Pooling
        │
        ▼
Genetic Algorithm
Feature Selection
        │
        ▼
Logistic Regression
        │
        ▼
Predicted Land Use Class
```

---

# 🧠 Model Components

| Component | Purpose |
|------------|----------|
| DenseNet-121 | Multi-scale Feature Extraction |
| Channel Attention | Channel-wise Feature Refinement |
| Spatial Attention | Spatial Feature Enhancement |
| Adaptive Gated Fusion | Multi-Level Feature Fusion |
| Transformer Encoder | Long-range Context Modeling |
| Genetic Algorithm | Optimal Feature Selection |
| Logistic Regression | Final Classification |

---

# ⚙️ Experimental Setup

| Parameter | Value |
|-----------|-------|
| Training | 70% |
| Validation | 15% |
| Testing | 15% |
| Dataset | EuroSAT RGB |
| Image Size | 64 × 64 |
| Optimizer | Adam |

---

# 📊 Performance Comparison

| Model | Test Accuracy |
|----------------------|-------------:|
| AlexNet | 91.95% |
| MobileNet-V2 | 93.88% |
| EfficientNet-B0 | 95.73% |
| ResNet-50 | 95.90% |
| DenseNet-121 | 96.77% |
| ⭐ Proposed MLFT | **97.36%** |

---

# 📈 Ablation Study

| Configuration | Test Accuracy |
|-------------------------------|-------------:|
| DenseNet-121 | 96.77% |
| DenseNet + Transformer | 96.92% |
| DenseNet + Feature Fusion + Transformer | 97.10% |
| ⭐ MLFT + Genetic Algorithm | **97.36%** |

---

# 📷 Experimental Results

## Confusion Matrix

<p align="center">
<img src="images/confusion_matrix.png" width="600">
</p>

---

## Attention Maps

<p align="center">
<img src="images/attention_maps.png" width="850">
</p>

---

## Feature Visualization (Optional)

<p align="center">
<img src="images/tsne.png" width="700">
</p>

---

# 📂 Repository Structure

```text
EuroSAT-LULC-Classification
│
├── dataset/
├── models/
├── notebooks/
├── images/
│   ├── architecture.png
│   ├── confusion_matrix.png
│   ├── attention_maps.png
│   └── tsne.png
│
├── results/
├── EuroSAT_Conference.pdf
├── requirements.txt
├── train.py
├── test.py
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/jaswanth-227/EuroSAT-LULC-Classification.git

cd EuroSAT-LULC-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Usage

Train the model

```bash
python train.py
```

Evaluate the model

```bash
python test.py
```

---

# 📄 Conference Paper

Read the complete paper:

📄 **EuroSAT_Conference.pdf**

---

# 🚀 Future Work

- Vision Transformers (ViT)
- Swin Transformers
- Multi-Spectral EuroSAT Classification
- Explainable AI using Grad-CAM
- Self-Supervised Learning
- Real-Time Satellite Analytics
- Lightweight Edge Deployment

---

# 👨‍💻 Author

**Jaswanth Yadurla**

B.Tech – Artificial Intelligence & Machine Learning

📧 **yadurlajaswanth@gmail.com**

🔗 **LinkedIn:** https://www.linkedin.com/in/jaswanth-yadurla-634290284/

---

# 📚 Citation

If you use this work, please cite:

```bibtex
@inproceedings{yadurla2025mlft,
  title={Multi-Scale Feature Fusion and Transformer Encoding for Enhanced Land Use Classification on EuroSAT},
  author={Yadurla, Jaswanth and others},
  booktitle={International Conference on Artificial Intelligence Applications and Technological Innovations (ICAIATI)},
  year={2025}
}
```

---

# 🙏 Acknowledgements

- ICAIATI 2025
- Taylor & Francis
- EuroSAT Dataset
- Sentinel-2 Mission
- Chaitanya Bharathi Institute of Technology (CBIT)

---

<p align="center">

⭐ **If you find this repository useful, please consider giving it a Star!**

Made with ❤️ by **Jaswanth Yadurla**

</p>
