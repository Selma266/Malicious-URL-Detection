# Malicious URL Detection using RoBERTa
<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-Hugging%20Face-blueviolet?style=for-the-badge&logo=Hugging%20Face&logoColor=white" alt="Transformers">
 </p>

 ### 📌 Project Overview
 
This project investigates the impact of class imbalance on a RoBERTa-based model for malicious URL detection.

The task is binary classification:

Benign URLs

Malicious (Phishing) URLs

The goal is to evaluate how different class distributions affect model performance and to examine the effectiveness of cost-sensitive learning in handling imbalance.

---

### 🎯 Objective

-Develop a malicious URL classifier using RoBERTa.

-Evaluate performance under different class imbalance ratios.

-Apply cost-sensitive learning for imbalanced scenarios.

-Compare results across all data distributions.

---

### 📊Experimental Setup:
**🤖 Model**

-Pretrained RoBERTa model

-Fine-tuned for binary classification

-Parameter-efficient fine-tuning using LoRA (Low-Rank Adaptation)


**📈 Experimental Scenarios**: Three class distribution settings were tested:

**S1**: Balanced dataset (50% benign / 50% malicious)

**S2**: Imbalanced dataset (90% benign / 10% malicious)

**S3**: Imbalanced dataset (10% benign / 90% malicious)


---
### ⚖️ Imbalance Handling Techniques
-For the imbalanced scenarios (S2 and S3), cost-sensitive learning was applied.

-Model performance was compared with and without imbalance handling.
### 📂 Dataset

The phishing URL dataset used in this project: https://data.mendeley.com/datasets/vfszbj9b36/1

## Implementation Note

- `roberta_v1.ipynb`: Baseline model without class imbalance handling.  
- `roberta_v2.ipynb`: Improved version including cost-sensitive learning to address class imbalance.
