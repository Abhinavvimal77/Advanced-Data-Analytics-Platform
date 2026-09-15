# Advanced Data Analytics – Modular Assignment 4

This repository contains the implementation and documentation for **Modular Assignment No. 4 – Practical Approach to Data Mining and Analytics**.

The project covers **Advanced Data Analytics, Machine Learning, SQL, REST APIs, Statistical Analysis, Financial Analytics, Data Optimization, and Performance Benchmarking**.

---

## 📌 Project Overview

The assignment demonstrates an end-to-end analytics workflow using Python and multiple real-world datasets.

The major components include:

* Data structure and memory optimization
* SQL analytics using SQLite
* Machine learning classification
* RFM customer segmentation
* K-Means clustering
* Revenue regression
* Financial market analysis
* World Bank economic analysis
* Statistical modelling
* Hypothesis testing
* REST API architecture
* Data visualization
* Performance benchmarking

---

## 📊 Datasets Used

The project works with four major data sources:

1. **Online Retail Dataset** – UCI Machine Learning Repository
2. **Titanic Passenger Dataset**
3. **Stock Market Data** – Yahoo Finance API
4. **World Bank Economic Data** – World Bank Open Data API

---

## 🤖 Machine Learning

The machine learning component includes:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* K-Means Clustering
* Linear Regression

The best Titanic classification model was **Gradient Boosting**, achieving:

```text
Accuracy: 81.01%
Cross-Validation Score: 81.90%
```

RFM-based K-Means clustering produced:

```text
Customers: 4,338
Clusters: 4
Silhouette Score: 0.6162
```

---

## 🗄️ SQL Analytics

SQLite was used to perform analytical queries involving:

* Revenue aggregation
* Customer segmentation
* Window functions
* CTEs
* RANK
* LAG
* Titanic survival analysis

---

## 📐 Statistical Analysis

The project includes statistical techniques implemented using Statsmodels:

* OLS Regression
* Logistic Regression
* ANOVA
* Chi-Square Test
* Shapiro-Wilk Normality Test
* Hypothesis Testing
* Confidence Intervals

---

## 📈 Financial Analytics

Stock market analysis was performed for:

* AAPL
* GOOGL
* MSFT
* AMZN
* META

The analysis includes:

* Daily returns
* Rolling volatility
* Correlation analysis
* Stock performance comparison

---

## 🚀 REST API

A Flask-based REST API architecture was demonstrated with endpoints for:

```text
GET  /api/revenue/summary
GET  /api/revenue/by-country
GET  /api/customers/segments
GET  /api/titanic/survival
GET  /api/stocks/performance
POST /api/predict/survival
```

---

## ⚡ Performance Highlights

### Memory Optimization

```text
Online Retail:
122.80 MB → 21.06 MB
82.9% reduction
```

### Vectorization Benchmark

```text
Loop:         52.2840 ms
Vectorized:    0.7062 ms
Pandas Apply: 117.4507 ms
```

### Revenue Analysis

```text
Total Revenue: £8,911,407.90
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Scikit-learn
* Statsmodels
* SQLite
* Flask
* Matplotlib
* Seaborn
* Plotly
* yfinance

---

## 📁 Repository Contents

### `MA_4_DMA.ipynb`

Jupyter Notebook containing the complete Python implementation, analysis, modelling, SQL operations, visualizations, API demonstration, and performance benchmarking.

### `MA_4.docx`

Detailed written assignment report documenting the methodology, datasets, analysis, results, and implementation.

### `Modular_Assignment-4_DMA.pdf`

PDF version of the complete assignment report.

---

## 👨‍💻 Author

**Abhinav M**

M.Sc. Statistics – Data Science
Vishwakarma University, Pune

---

## 🎓 Academic Information

**Course:** Practical Approach to Data Mining and Analytics

**Assignment:** Modular Assignment No. 4

**Module:** Advanced Data Analytics, Machine Learning, SQL, REST APIs & Financial Analytics

**Academic Year:** 2025–2026

---

## ⚠️ Disclaimer

This project was developed for academic and educational purposes.

Financial analysis presented in this project should not be considered financial advice.
