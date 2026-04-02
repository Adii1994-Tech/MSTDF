# 🚀 Intrusion Detection System (IDS) for IIoT Networks

This repository contains the implementation of a deep learning-based Intrusion Detection System (IDS) designed for Industrial Internet of Things (IIoT) environments. The proposed approach is evaluated on multiple benchmark datasets and includes an intrinsic interpretability analysis.


## 📂 Repository Structure

├── 1. Proposed IDS on CICIoMT2024 dataset.ipynb
├── 2. Proposed IDS without BVAE Technique on CICIoMT2024 dataset.ipynb
├── 3. Proposed IDS on EDGEIIoTset Dataset.ipynb
├── 4. Proposed IDS without BVAE Technique on EDgeIIoTset Dataset.ipynb
├── 5. UMAP Visualization.ipynb
├── 6. Intrinsic interpretability.ipynb
├── 7. Ablation Study .ipynb
└── README.md

## 🔹 Notebooks Description

### 1. Proposed IDS on CICIoMT2024 Dataset
- Full implementation of the proposed IDS model  
- Includes BVAE-based feature representation  
- Covers preprocessing, training, and evaluation  

### 2. Proposed IDS without BVAE (CICIoMT2024)
- Baseline model without BVAE  
- Used for comparative analysis to highlight performance gain  

### 3. Proposed IDS on EDGE-IIoTset Dataset
- Evaluation of the proposed model on EDGE-IIoTset  
- Demonstrates robustness and generalization  

### 4. Proposed IDS without BVAE (EDGE-IIoTset)
- Baseline comparison on EDGE-IIoTset  
- Helps quantify the contribution of BVAE  

### 5. UMAP Visualization
- Visualizes high-dimensional feature representations  
- Shows clustering of normal vs attack traffic  

### 6. Intrinsic Interpretability
- Explains model decision-making process  
- Provides insights into learned feature importance  

### 7. Ablation Study
- Evaluates contribution of different model components  
- Demonstrates effectiveness of each module  

## ⚙️ Requirements

Ensure you have **Python 3.8+** installed.

### 📦 Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scikit-plot tensorflow keras jupyter umap-learn
