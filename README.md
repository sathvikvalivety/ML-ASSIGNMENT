# Hybrid Image Feature Extraction and Classification

## 📌 Project Overview
A comprehensive implementation of hybrid image classification combining traditional computer vision techniques (HOG, LBP, Edge Detection) with deep learning (ResNet) features, enhanced with dynamic feature selection.

## 👥 Authors
- **N. Abhinay Reddy** (CH.SC.U4CYS23029)
- **V. Sathvik** (CH.SC.U4CYS23050)

## 🚀 Key Features
- **Hybrid Feature Fusion**: Combines HOG texture features with ResNet deep features
- **Dynamic Attention Mechanism**: Learns optimal feature weights
- **Multiple Implementations**:
  - HOG + Logistic Regression
  - LBP + KNN
  - Edge Detection + Random Forest
  - ResNet Feature Extraction
  - Hybrid (HOG+ResNet) with Attention
- **Performance Analysis**: Accuracy, Precision, Recall, F1-Score metrics
- **Computational Efficiency**: Execution time tracking

## 🛠 Installation
git clone https://github.com/yourusername/image-classification-hybrid.git
cd image-classification-hybrid
pip install -r requirements.txt

├── data/                   # Dataset storage
│   ├── raw/                # Raw images
│   └── processed/          # Processed data
├── models/                 # Saved models
├── notebooks/              # Jupyter notebooks
├── src/
│   ├── feature_extraction/ # Feature extraction modules
│   ├── training/           # Model training scripts
│   ├── evaluation/         # Performance evaluation
│   └── utils/              # Helper functions
├── README.md
└── requirements.txt
