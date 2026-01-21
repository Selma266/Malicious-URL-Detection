# Malicious-URL-Detection
<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-Hugging%20Face-blueviolet?style=for-the-badge&logo=Hugging%20Face&logoColor=white" alt="Transformers">
 </p>
My first project focuses on analyzing the impact of class imbalance on RoBERTa-based malicious URL detection. 
I study how detection performance changes under different data distributions: when benign URLs greatly outnumber malicious ones, when malicious URLs dominate, and when both classes are balanced.

---

### 🎯 Objective

-**Task**: Classification of URLs into benign or malicious (phishing).

-**Model**: Use of the RoBERTa model for URL classification, without major modifications to the base architecture.

-**Study Focus**: Investigation of the impact of class imbalance on the performance of the RoBERTa model.

---

### 📊Experimental Scenarios:

-**S1**: Balanced dataset (50% benign / 50% malicious)

-**S2**: Imbalanced dataset (90% benign / 10% malicious)

-**S3**: Imbalanced dataset (10% benign / 90% malicious)


---
### ⚖️ Imbalance Handling Techniques
-Application of **SMOTE** and **SMOTE-Tomek** to address class imbalance in S2 and S3

-Comparative analysis of the impact of these techniques on model performance
