<div align="center">

# 🛒 Shop Smart
### Predicting Online Customer Purchase Intent using Machine Learning

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge"/>

*A machine learning pipeline for predicting customer purchase behavior from online shopping session data.*

</div>

---

## 🚀 Overview

Understanding whether a customer is likely to make a purchase is one of the most valuable predictive tasks in e-commerce.

This project develops an end-to-end Machine Learning pipeline that analyzes customer browsing sessions and predicts purchase intent using behavioral analytics, feature engineering, and supervised learning models.

The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## ✨ Features

- 📊 Comprehensive Exploratory Data Analysis
- 📈 Customer Behaviour Analysis
- ⚙️ Feature Engineering
- 🧹 Data Cleaning & Preprocessing
- 🌲 Decision Tree Classifier
- 🌳 Random Forest Classifier
- 🎯 Hyperparameter Tuning
- 📉 Confusion Matrix Visualization
- 📌 Classification Metrics
- 📊 Correlation & Pairplot Analysis

---

# 📂 Dataset

**Dataset:** Online Shoppers Purchasing Intention Dataset

| Property | Value |
|-----------|-------|
| Samples | 12,330 |
| Original Features | 18 |
| Engineered Features | 4 |
| Target | Revenue |

The dataset contains user browsing behavior including:

- Administrative Activity
- Product Related Activity
- Page Values
- Bounce Rate
- Exit Rate
- Traffic Source
- Visitor Type
- Weekend Activity
- Region
- Browser Information

---

# 🏗️ Project Architecture

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Categorical Encoding
      │
      ▼
Train/Test Split
      │
      ▼
Decision Tree
      │
      ├─────────────┐
      ▼             ▼
Hyperparameter   Random Forest
   Tuning             │
      │               │
      └──────┬────────┘
             ▼
 Performance Evaluation
```

---

# 📊 Exploratory Data Analysis

The project includes multiple visualization techniques to better understand customer behavior.

### Distribution Analysis

- Revenue Distribution
- Visitor Type Distribution
- Monthly Distribution
- Traffic Type Distribution

---

### Numerical Feature Analysis

- Product Related Duration
- Page Values
- Bounce Rates
- Exit Rates

---

### Outlier Detection

- Boxplots
- Distribution Curves

---

### Relationship Analysis

- Correlation Heatmap
- Pairplot
- Bivariate Analysis

---

# ⚡ Feature Engineering

Instead of relying solely on the original dataset, additional features were engineered to capture customer engagement.

| Feature | Description |
|----------|-------------|
| Total Duration | Total browsing time |
| Total Pages | Total pages visited |
| Avg Product Page | Average time per product page |
| Engagement Score | Browsing intensity score |

---

# 🤖 Machine Learning Models

## Decision Tree

- Baseline classifier
- Hyperparameter tuning
- Pre-pruning

Optimized using:

- `max_depth`
- `min_samples_split`
- `min_samples_leaf`

---

## Random Forest

Used as an ensemble learning model to compare performance against the optimized Decision Tree.

---

# 📈 Evaluation Metrics

Model performance was evaluated using

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Development | Jupyter Notebook |

---

# 📁 Directory Structure

```text
Shop-Smart/
│
├── data/
│   └── shop_smart_ecommerce.csv
│
├── notebook/
│   └── Shop_Smart_Ecommerce.ipynb
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---


# 📌 Future Work

- Cross Validation
- GridSearchCV
- Feature Importance Analysis
- SHAP Explainability
- Streamlit Dashboard
- Flask Deployment
- Docker Containerization

---

# 💡 Potential Applications

- Purchase Prediction
- Recommendation Systems
- Customer Segmentation
- Marketing Analytics
- Sales Forecasting
- Conversion Rate Optimization

---

# 👨‍💻 Author

**Rishiraj De**

Computer Science Engineering Student

> Passionate about Machine Learning, Data Science, and Building Intelligent Systems.

---

<div align="center">

⭐ **If you found this repository useful, consider starring it!**

</div>
