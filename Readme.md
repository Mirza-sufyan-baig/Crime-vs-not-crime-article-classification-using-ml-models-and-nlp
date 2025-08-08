# 🕵️ Crime vs Not Crime Classification

This project classifies text articles into two categories — **Crime** or **Not Crime** — using multiple machine learning approaches.  
The dataset used is `CrimeVsNotCrimeArticles.csv`, which contains labeled articles.

## 📌 Project Overview

I implemented and compared three different classification approaches:

1. **Decision Tree Classifier**
2. **K-Nearest Neighbors (KNN)**
3. **Stacking Classifier**  
   - Base Models: Logistic Regression, Complement Naive Bayes, Decision Tree

Each method is in a separate Jupyter Notebook for clarity.

---

## 📂 Files in This Repository

- `01_DecisionTree.ipynb` → Classification using Decision Tree
- `02_KNN.ipynb` → Classification using K-Nearest Neighbors
- `03_StackingClassifier.ipynb` → Classification using Logistic Regression, Complement Naive Bayes, and Decision Tree
- `CrimeVsNotCrimeArticles.csv` → Dataset containing articles and labels
- `requirements.txt` → List of dependencies

---

## 📊 Dataset

- **File:** `CrimeVsNotCrimeArticles.csv`
- **Columns:**
  - `text` → The article text
  - `label` → `1` for crime-related, `0` for not crime-related
- The dataset is pre-labeled for supervised learning.

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/crime-vs-not-crime.git
   cd crime-vs-not-crime
