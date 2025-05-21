# 📊 A Comparative Analysis of Machine Learning and Deep Learning for Sentiment Analysis

This repository provides a detailed comparative analysis of traditional machine learning and modern deep learning models on sentiment classification of user reviews from the Google Play Store. This project includes code, dataset, research papers, and evaluation results.

---

## 📝 Table of Contents

- [Project Overview](#project-overview)
- [Contents](#contents)
- [Methodology](#methodology)
- [Models Compared](#models-compared)
- [Dataset](#dataset)
- [Results](#results)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Citation](#citation)
- [Contact](#contact)
- [License](#license)
- [Availability](#availability)

---

## 🔍 Project Overview

The project compares the accuracy and performance of various models—both machine learning and deep learning—in classifying Google Play user reviews into positive or negative sentiment. It also integrates sentiment dictionaries and evaluates the effect of sampling strategies and embeddings.

---

## 📂 Contents


---

## ⚙️ Methodology

1. **Data Collection**: Reviews were scraped from Google Play Store.
2. **Preprocessing**: Included cleaning text, removing HTML tags, and normalization.
3. **Feature Engineering**: TF-IDF and custom sentiment lexicons (HowNet, NTUSD, iSGoPaSD).
4. **Word Embedding**: Word2Vec (CBOW and Skip-gram).
5. **Model Training**:
   - Traditional ML: Naïve Bayes, SVM, Logistic Regression, Random Forest, XGBoost
   - Deep Learning: Bi-LSTM with Keras
6. **Evaluation**: Metrics include accuracy, precision, recall, F1-score, and ROC-AUC.

---

## 🧠 Models Compared

| Model              | Accuracy (%) | AUC Score |
|-------------------|--------------|-----------|
| Logistic Regression | 84.79       | 0.92      |
| Bi-LSTM             | 84.58       | 0.93      |
| Random Forest       | 84.10       | 0.92      |
| SVM                 | 83.89       | 0.91      |
| XGBoost             | 83.68       | 0.91      |
| Naïve Bayes         | 83.12       | 0.90      |

---

## 📊 Dataset

- File: `data/Google Play Reviews.csv`
- Source: Web-scraped reviews from Google Play Store
- Classes: Positive and Negative sentiments
- Total Samples: ~10,700

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/grandmaster-01/Sentiment-Analysis-ML.git
cd Sentiment-Analysis-ML

@article{naik2025comparative,
  title={A Comparative Analysis of Machine Learning and Deep Learning Approaches for Sentiment Classification on Google Play Reviews},
  author={Umesh Naik and Charan S.B},
  year={2025},
  journal={Chanakya University - MSC Data Science / MCA Research},
  note={Available at GitHub: https://github.com/grandmaster-01/Sentiment-Analysis-ML}
}

Academic and Research Use License

Copyright (c) 2025 Umesh Naik and Charan S.B

This project is provided for **academic and research purposes only**.

You are allowed to:

- Use, copy, and modify the code and content for non-commercial academic or research use.
- Share and cite the project in theses, publications, or educational settings with appropriate attribution.

You are **not allowed to**:

- Use this code or any part of it for commercial, for-profit, or production purposes.
- Re-distribute modified versions without clear credit to the original authors.

DISCLAIMER:  
The software and related content are provided "AS IS", without any warranties of any kind, express or implied.
The authors are not liable for any claims, damages, or other liabilities that may arise from its use.

To request permissions for use beyond research and education, please contact the authors directly.

