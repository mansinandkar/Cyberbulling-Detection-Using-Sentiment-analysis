# 🛡️ Cyberbullying Detection using Sentiment Analysis 

## 📌 Project Overview
This project implements an **end-to-end supervised machine learning pipeline** for detecting cyberbullying in social media text using **sentiment analysis and classical NLP techniques**.

The solution focuses on **robust preprocessing, feature engineering, class imbalance handling, model benchmarking, and deployment-ready inference**, achieving **92.98% accuracy** using a TF-IDF + SVM classifier.

The project is designed and implemented with an **ML Engineer mindset**, emphasizing reproducibility, experimentation rigor, and real-world deployment readiness.

---

## 🎯 Motivation

Cyberbullying on social media platforms poses serious psychological and social risks, yet manual moderation is not scalable due to the volume, velocity, and linguistic complexity of user-generated content. Existing rule-based systems struggle to generalize across evolving language patterns, sarcasm, and contextual abuse.

The motivation behind this project is to design a robust, data-driven NLP pipeline that can automatically detect cyberbullying with high precision and recall, while addressing real-world challenges such as class imbalance, noisy text, and deployment readiness. The goal is to bridge the gap between academic NLP models and practical, production-oriented machine learning systems capable of supporting content moderation at scale.

---

## 🎯 Problem Statement
Cyberbullying on social media platforms is:
- High-volume
- Linguistically complex
- Difficult to moderate manually

This project addresses the problem by building an **automated classification system** that identifies whether a given tweet contains cyberbullying content or not.

---

## 🧠 Key ML Engineering Highlights
- Designed a **modular NLP pipeline** from raw text to deployment
- Handled **severe class imbalance** using SMOTE
- Benchmarked multiple **model–feature combinations**
- Applied **cross-validation** to ensure generalization
- Deployed the best-performing model locally using **Flask**
- Used **joblib** for efficient model serialization and inference

---

## 🧪 Dataset Summary
- ~48,000+ tweets after class balancing
- Aggregated from public datasets (academic and Kaggle sources)
- Binary classification:
  - Cyberbullying
  - Non-cyberbullying
- Strong class imbalance corrected using SMOTE

---

## 🔄 Architecture
<img width="986" height="707" alt="Proposed Methodology" src="https://github.com/user-attachments/assets/b2aab1ce-5453-4b15-b5db-be4a4b2f7ef6" />

---

## 🏆 Best Model Performance

Model: Support Vector Machine (SVM)
Feature Engineering: TF-IDF
Accuracy: 92.98%
F1-Score: 92.98%
ROC-AUC: 0.98

---


## 🚀 Deployment Architecture
- Serialized trained model and vectorizer using **joblib**
- Exposed inference through a **Flask REST API**
- Frontend interaction using **HTML + JavaScript**
- Real-time text classification


---


## 📰 Publications
- https://ieeexplore.ieee.org/document/10467658
- https://journal.esrgroups.org/jes/article/view/4992/3641/9188

---

## 🤝 Contributors
- Mansi Nandkar
- Avantika Jalote
- Kevin Ninan Mathew
- Karim Sohail Khan Patan


