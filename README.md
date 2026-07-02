# 🌍 Multi-Scale Feature Fusion & Transformer Encoding for EuroSAT Land Use Classification

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3500&pause=1000&color=00C4FF&center=true&vCenter=true&width=900&lines=EuroSAT+Land+Use+Classification;Multi-Scale+Feature+Fusion;Transformer+Encoding;Genetic+Algorithm+Feature+Selection;ICAIATI+2025+Best+Paper+Award" />
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge&logo=pytorch)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Research](https://img.shields.io/badge/Research-ICAIATI%202025-success?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-97.36%25-brightgreen?style=for-the-badge)

</p>

---

# 📖 Overview

This repository contains the implementation of our **ICAIATI 2025 Best Paper Award-winning research**, proposing a hybrid deep learning framework for **Land Use and Land Cover (LULC) Classification** using the EuroSAT satellite imagery dataset.

The framework combines:

- 🧠 DenseNet-121 Multi-scale Feature Extraction
- 🎯 Channel & Spatial Attention
- 🔀 Adaptive Gated Feature Fusion
- 🤖 Transformer Encoder
- 🧬 Genetic Algorithm Feature Selection
- 📈 Machine Learning Classifiers

The proposed model achieved **97.36% classification accuracy**, outperforming several state-of-the-art CNN architectures.

---

# 🏆 Achievements

- 🥇 **Best Paper Award – ICAIATI 2025**
- 📄 Research accepted for publication in **Taylor & Francis**
- 🚀 Achieved **97.36% Test Accuracy** on the EuroSAT benchmark dataset
- 🌍 Developed a hybrid CNN–Transformer framework for remote sensing image classification

---

# 🎯 Applications

This work can be applied to:

- 🌾 Agricultural Monitoring
- 🏙 Urban Planning
- 🌍 Land Use Mapping
- 🌳 Environmental Monitoring
- 🚨 Disaster Management
- 🛰 Remote Sensing Analytics

---

# 📂 Dataset

**Dataset:** EuroSAT (Sentinel-2 Satellite Imagery)

📊 **Dataset Statistics**

| Attribute | Value |
|-----------|-------|
| Images | 27,000 |
| Classes | 10 |
| Resolution | 64 × 64 |
| Source | Sentinel-2 RGB |

### Classes

- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- Industrial
- Pasture
- PermanentCrop
- Residential
- River
- Sea/Lake

---

# 🏗 Proposed Architecture

The complete processing pipeline consists of:

```text
Satellite Image
        │
        ▼
DenseNet-121
Multi-scale Features
        │
        ▼
Channel Attention
        │
        ▼
Spatial Attention
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
Machine Learning Classifier
        │
        ▼
Land Use Prediction
```

---

# 🧠 Model Components

| Module | Purpose |
|---------|---------|
| DenseNet-121 | Multi-scale feature extraction |
| Channel Attention | Channel refinement |
| Spatial Attention | Spatial feature enhancement |
| Adaptive Gated Fusion | Multi-level feature fusion |
| Transformer Encoder | Global contextual learning |
| Genetic Algorithm | Feature selection |
| Logistic Regression | Final classification |

---

# ⚙ Experimental Setup

| Parameter | Value |
|-----------|-------|
| Training | 70% |
| Validation | 15% |
| Testing | 15% |
| Optimizer | Adam |
| Dataset | EuroSAT |
| Image Size | 64×64 |

---

# 📊 Performance Comparison

| Model | Test Accuracy |
|---------|-------------:|
| AlexNet | 91.95% |
| MobileNetV2 | 93.88% |
| EfficientNet-B0 | 95.73% |
| ResNet-50 | 95.90% |
| DenseNet-121 | 96.77% |
| ⭐ Proposed Model | **97.36%** |

---

# 📈 Ablation Study

| Configuration | Accuracy |
|---------------|----------|
| DenseNet-121 | 96.77% |
| DenseNet + Transformer | 96.92% |
| DenseNet + Fusion + Transformer | 97.10% |
| ⭐ Full Model + GA | **97.36%** |

---

# 📂 Repository Structure

```text
EuroSAT-LULC-Classification
│
├── dataset/
├── models/
├── notebooks/
├── results/
├── images/
├── architecture/
├── EuroSAT_Conference.pdf
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/EuroSAT-LULC-Classification.git

cd EuroSAT-LULC-Classification

pip install -r requirements.txt
```

---

# ▶ Usage

Run the training pipeline

```bash
python train.py
```

Evaluate the model

```bash
python test.py
```

---

# 📄 Conference Paper

📥 **Read the Full Paper**

```
EuroSAT_Conference.pdf
```

---

# 🔬 Future Work

- Vision Transformers (ViT)
- Swin Transformer
- Multi-Spectral EuroSAT
- Self-Supervised Learning
- Explainable AI (Grad-CAM)
- Real-Time Remote Sensing Pipeline

---

# 👨‍💻 Authors

**Jaswanth Yadurla**

B.Tech – Artificial Intelligence & Machine Learning

📧 yadurlajaswanth@gmail.com

---

# 📚 Citation

If you use this work, please cite our paper.

```bibtex
@inproceedings{jaswanth2025eurosat,
  title={Multi-Scale Feature Fusion and Transformer Encoding for EuroSAT Land Use Classification},
  author={Yadurla, Jaswanth and others},
  booktitle={ICAIATI 2025},
  year={2025}
}
```

---

# ⭐ Support

If you found this repository useful, please consider giving it a ⭐.

**Built with ❤️ for Remote Sensing, Computer Vision, and Artificial Intelligence.**
