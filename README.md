# 📰 BBC News Text Mining: Classification & Clustering

**Text Mining** | Università degli Studi di Milano-Bicocca | A.A. 2025/2026
*Alberto Cera, Davide Fabio Loreti, Carlo Pegoraro*

## 📌 Overview
Complete text mining pipeline for classification and clustering of BBC News articles (5 categories) using both sparse (TF-IDF) and dense (BERT) text representations.

## 🛠️ Tech Stack
**NLP:** TF-IDF, BERT, sentence-transformers
**ML:** Scikit-learn, SVM, Logistic Regression, Random Forest, KMeans
**Other:** Python, Pandas, NumPy, Matplotlib, Seaborn

## 📊 Results
**Best classifier:** TF-IDF + SVM → 97.99% accuracy, F1 0.98
**Best clustering:** Embeddings + KMeans (k=5) → aligned with true categories

## 📁 Structure data/
raw/bbc-fulltext/
processed/
notebooks/
01_data_loading_eda.ipynb
02_preprocessing.ipynb
03_text_representation.ipynb
04_text_classification.ipynb
05_text_clustering.ipynb
requirements.txt

## ⚙️ How to Run
pip install -r requirements.txt

Run notebooks in order from 01 to 05.
