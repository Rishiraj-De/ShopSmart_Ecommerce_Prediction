# 🛒 Shop Smart - E-Commerce Purchase Prediction

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

### Predicting Online Customer Purchase Intent using Machine Learning

</div>

---

# 📖 Overview

**Shop Smart** is a Machine Learning project that predicts whether an online visitor is likely to complete a purchase based on their browsing behavior during a website session.

The project applies **Exploratory Data Analysis (EDA)**, **Feature Engineering**, **Data Preprocessing**, and **Machine Learning Classification** techniques to analyze customer interactions and predict purchase intent.

The goal is to help e-commerce businesses identify potential buyers, improve marketing campaigns, increase conversion rates, and understand customer behavior.

---

# 🎯 Objectives

- Analyze customer browsing behavior.
- Explore important features affecting purchases.
- Perform data visualization using EDA.
- Engineer meaningful features from raw data.
- Train Machine Learning models for purchase prediction.
- Compare model performance using classification metrics.

---

# 📂 Dataset

The project uses the **Online Shoppers Purchasing Intention Dataset**.

### Dataset Summary

| Property | Value |
|----------|--------|
| Total Records | 12,330 |
| Original Features | 18 |
| Engineered Features | 4 |
| Final Features | 22 |
| Target Variable | Revenue |

### Important Features

- Administrative Pages
- Administrative Duration
- Informational Pages
- Informational Duration
- Product Related Pages
- Product Related Duration
- Bounce Rates
- Exit Rates
- Page Values
- Special Day
- Month
- Operating System
- Browser
- Region
- Traffic Type
- Visitor Type
- Weekend
- Revenue (Target)

---

# 🧠 Project Workflow

```
Dataset
    │
    ▼
Data Inspection
    │
    ▼
Missing Value Analysis
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Feature Engineering
    │
    ▼
Label Encoding
    │
    ▼
Train-Test Split
    │
    ▼
Model Training
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Model Evaluation
```

---

# 📊 Exploratory Data Analysis

Several visualizations were created to better understand the dataset.

## Univariate Analysis

- Revenue Distribution
- Monthly Distribution
- Visitor Type Distribution
- Traffic Type Distribution

---

## Distribution Analysis

Histogram plots were created for:

- Product Related Duration
- Page Values
- Bounce Rates
- Exit Rates

---

## Outlier Detection

Boxplots were used to identify outliers in:

- Product Related Duration
- Product Related Pages
- Administrative Duration
- Page Values

---

## Bivariate Analysis

Relationship between Revenue and:

- Visitor Type
- Month
- Weekend
- Traffic Type

---

## Correlation Analysis

The project includes

- Correlation Heatmap
- Pair Plot

to understand feature relationships.

---

# ⚙️ Feature Engineering

Four new features were created to improve prediction performance.

### 1. Total Duration

```python
Administrative Duration
+ Informational Duration
+ Product Related Duration
```

---

### 2. Total Pages

```python
Administrative
+ Informational
+ Product Related
```

---

### 3. Average Product Page Time

```python
ProductRelatedDuration
/
(ProductRelated + 1)
```

---

### 4. Engagement Score

```python
Total Pages × Total Duration
```

These engineered features provide better insight into customer engagement during browsing sessions.

---

# 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Label Encoding of categorical variables
- Feature Engineering
- Train-Test Split (80:20)

---

# 🤖 Machine Learning Models

The following classification models were implemented:

## Decision Tree Classifier

- Baseline Model
- Hyperparameter tuning performed

Parameters tuned:

- max_depth
- min_samples_split
- min_samples_leaf

---

## Random Forest Classifier

Random Forest was trained and evaluated to compare its performance with the Decision Tree model.

---

# 📈 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

These metrics provide a comprehensive understanding of classification performance.

---

# 🛠️ Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Machine Learning

- Decision Tree Classifier
- Random Forest Classifier

---

# 📁 Project Structure

```
Shop-Smart-Ecommerce/
│
├── data/
│   └── shop_smart_ecommerce.csv
│
├── notebook/
│   └── Shop_Smart_Ecommerce.ipynb
│
├── images/
│   ├── univariate_analysis.png
│   ├── histogram_analysis.png
│   ├── boxplots.png
│   ├── heatmap.png
│   ├── pairplot.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Shop-Smart-Ecommerce.git
```

Move into the project directory

```bash
cd Shop-Smart-Ecommerce
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Run

```
Shop_Smart_Ecommerce.ipynb
```

---

# 📋 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

or install manually

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

---

# 📊 Results

The project successfully predicts customer purchase intent using browsing behavior and engineered features.

Key achievements include:

- Comprehensive Exploratory Data Analysis
- Effective Feature Engineering
- Customer Behavior Analysis
- Decision Tree Hyperparameter Optimization
- Performance Comparison with Random Forest
- Evaluation using multiple classification metrics

---

# 💼 Real-World Applications

This project can be used for:

- Customer Purchase Prediction
- Targeted Marketing
- Personalized Recommendations
- Customer Segmentation
- Conversion Rate Optimization
- E-commerce Analytics
- Business Intelligence
- Sales Forecasting

---

# 🔮 Future Improvements

- Implement Gradient Boosting algorithms
- Perform GridSearchCV optimization
- Apply Cross Validation
- Build a Streamlit Web Application
- Deploy the model using Flask or FastAPI
- Add SHAP Explainability
- Build an interactive dashboard using Power BI

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Submit a Pull Request.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Rishiraj De**

Computer Science Engineering Student

**Areas of Interest**

- Artificial Intelligence
- Machine Learning
- Data Science
- Computer Vision
- Full Stack Development

---

<div align="center">

### ⭐ If you found this project helpful, don't forget to star the repository!

**Happy Coding! 🚀**

</div>
