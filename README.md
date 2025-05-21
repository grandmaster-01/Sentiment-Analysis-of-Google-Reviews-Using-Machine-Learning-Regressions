# 📊 A Comparative Analysis of Machine Learning and Deep Learning for Sentiment Analysis

This repository presents a comprehensive comparative study of various machine learning and deep learning models applied to sentiment classification of user reviews from Google Play Store. The goal is to evaluate the performance of traditional models versus deep learning approaches in identifying the sentiment polarity (positive/negative) of app reviews.

## 📝 Table of Contents

- [Project Overview](#project-overview)
- [Models Compared](#models-compared)
- [Dataset](#dataset)
- [Results](#results)
- [Folder Structure](#folder-structure)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Reference Paper](#reference-paper)
- [License](#license)

## 🔍 Project Overview

The project analyzes sentiment using:
- Traditional ML models: Naïve Bayes, SVM, Logistic Regression, Random Forest, XGBoost
- Deep learning model: Bi-LSTM (Bidirectional LSTM)

### Objectives:
1. Compare accuracy and AUC of machine learning and deep learning approaches.
2. Utilize custom and standard sentiment dictionaries (iSGoPaSD, HowNet, NTUSD).
3. Explore sampling strategies and word embeddings to improve performance.

## 🧠 Models Compared

| Model              | Accuracy (%) | AUC Score |
|-------------------|--------------|-----------|
| Logistic Regression | 84.79       | 0.92      |
| Bi-LSTM             | 84.58       | 0.93      |
| Random Forest       | 84.10       | 0.92      |
| SVM                 | 83.89       | 0.91      |
| XGBoost             | 83.68       | 0.91      |
| Naïve Bayes         | 83.12       | 0.90      |

## 📊 Dataset

The dataset contains over 10,000 user reviews scraped from the Google Play Store. Each review is labeled as **positive** or **negative** based on the app rating and content. Preprocessing steps included removing HTML, tokenization, and vectorization using TF-IDF and Word2Vec.

Dataset file: `data/Google Play Reviews.csv`

## 📁 Folder Structure

