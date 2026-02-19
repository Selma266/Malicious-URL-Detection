# Malicious URL Detection using RoBERTa
<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-Hugging%20Face-blueviolet?style=for-the-badge&logo=Hugging%20Face&logoColor=white" alt="Transformers">
 </p>

 ###📌 Project Overview
This project analyzes how class imbalance affects the performance of a RoBERTa-based model for malicious URL detection.
The task is binary classification:
Benign URLs
Malicious (Phishing) URLs
The main objective is to evaluate how different class distributions influence detection performance and how cost-sensitive learning helps address imbalance issues.

---

### 🎯 Objective

-Build a URL classification model using RoBERTa (base architecture).

-Evaluate model performance under different class imbalance scenarios.

-Apply cost-sensitive learning to handle imbalanced datasets.

-Compare performance across different data distributions.

---

### 📊Experimental Setup:
-**🤖 Model**

-Pretrained RoBERTa model

-No major modifications to the base architecture

-Fine-tuned for binary URL classification

-Parameter-efficient fine-tuning using LoRA (Low-Rank Adaptation)
-**📈 Experimental Scenarios**
Three class distribution settings were tested:

-**S1**: Balanced dataset (50% benign / 50% malicious)

-**S2**: Imbalanced dataset (90% benign / 10% malicious)

-**S3**: Imbalanced dataset (10% benign / 90% malicious)


---
### ⚖️ Imbalance Handling Techniques
-For the imbalanced scenarios (S2 and S3), cost-sensitive learning was applied.
-Performance was compared with and without imbalance handling.
### 📂 Dataset

The phishing URL dataset used in this project: https://data.mendeley.com/datasets/vfszbj9b36/1
