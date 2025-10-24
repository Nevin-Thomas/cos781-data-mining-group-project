# COS781-data-mining-group-project
# Semantic Feature Reduction for Text Classification

## Project Overview
This project develops a **semantic feature reduction pipeline** for text classification using **Word2Vec embeddings** and **graph-based clustering**.  
By grouping semantically similar words and combining them with traditional feature selection methods, it aims to improve **classification accuracy** and **computational efficiency** compared to traditional BoW and TF-IDF approaches.

---

## 🎯 Research Questions
- **Problem:**  
  Traditional text classification methods like Bag-of-Words and TF-IDF ignore semantic similarity between words (e.g., “Apple” and “Banana” as fruits), increasing computational cost and reducing accuracy.  
  This project investigates how to **reduce features while retaining semantic meaning** to improve model performance.
  
- **Why it’s interesting:**  
  With massive amounts of text data generated daily, enhancing feature reduction and classification efficiency is highly relevant for modern NLP applications.

---

## 📊 Data
- Dataset: *TBD*  
- Data Size: *TBD*  
- Attributes: *TBD*

---

## ⚙️ Approach
1. **Word2Vec** – for word embeddings capturing semantic relationships.  
2. **Graph-Based Clustering** – to group semantically similar words using cosine similarity or graph search.  
3. **Dimensionality Reduction** – combine semantic clustering with Mutual Information, Term Frequency, or Chi-Square.  
4. **Classifiers** – Naïve Bayes, SVM, KNN, Random Forest, and possibly deep learning models like LSTMs.  

### 🧩 Expected Outcomes
- A semantic feature reduction pipeline implementation.  
- Comparative evaluation of reduced vs. traditional feature sets.  
- Improved efficiency and/or accuracy across classifiers.  

---

## 📈 Evaluation
**Metrics:**  
- Accuracy, Precision, Recall, F1-Score  
- Computational Efficiency (training/testing time, memory usage)  
- Feature Space Size Reduction  

**Baselines:**  
1. Bag-of-Words + Classifiers  
2. TF-IDF + Classifiers  
3. Word2Vec without Clustering  

---

## 👥 Team Members

| Member Name | Student Number | Role | Contact | Description |
|--------------|----------------|------|----------|--------------|
| *N Thomas* | *20435216* |  | *u20435216@tuks.co.za* | - |
| *M Dukhanti* | *22617541* |  | *u22617541@tuks.co.za* | - |
| *B Dlamini* | *21739120* |  | *u21739120@tuks.co.za* | - |
| *N Cele* | *25717342* |  | *u25717342@tuks.co.za* | - |

---

## 🧾 Expected Outputs
- ✅ Implementation of the semantic feature reduction pipeline  
- 📊 Comparative results and visualizations  
- ⚡ Demonstration of efficiency and accuracy improvements  
- 🧠 Final written report with analysis and future recommendations  

---

## 🛠️ Technologies Used
- **Python**
- **Google Colab**
- **Word2Vec**
- **scikit-learn**
- **NetworkX / Graph libraries**
- **Matplotlib / Seaborn**

---

## 📚 License
This project is licensed under the [MIT License](LICENSE).

---

⭐ *Developed collaboratively for a Data Mining course project.*
