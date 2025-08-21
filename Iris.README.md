# 🌸 Iris Flower Classification using Logistic Regression

This project implements a *Machine Learning classification model* on the famous *Iris dataset* 🌸.  
The goal is to classify flowers into *Setosa, Versicolor, or Virginica* species based on their sepal and petal features.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Data Preprocessing](#-data-preprocessing)
- [Visualization](#-visualization)
- [Model Training](#-model-training)
- [Results](#-results)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 Overview
The *Iris dataset* is one of the most well-known datasets in pattern recognition.  
This project demonstrates:
- *Exploratory Data Analysis (EDA)*
- *Visualization of features*
- *Correlation analysis*
- *Feature scaling*
- *Model training with Logistic Regression*
- *Evaluation using Accuracy & Confusion Matrix*

---

## 📂 Dataset
- The dataset is loaded from *Kaggle’s Iris dataset*.  
- It contains *150 samples* with the following features:

| Feature          | Description |
|------------------|-------------|
| SepalLengthCm    | Sepal length in cm |
| SepalWidthCm     | Sepal width in cm |
| PetalLengthCm    | Petal length in cm |
| PetalWidthCm     | Petal width in cm |
| Species          | Setosa / Versicolor / Virginica |

---

## ✨ Features of this Project
- Data Cleaning & Preprocessing  
- Boxplots & Pairplots for feature distributions  
- Heatmap for correlation analysis  
- Label Encoding for categorical output  
- Logistic Regression Model Training  
- Confusion Matrix visualization for evaluation  

---

## 🛠 Data Preprocessing
1. Dropped unnecessary columns (Id).  
2. Checked for *null values* (none present).  
3. Applied *Label Encoding* to the Species column.  
4. Standardized features using *StandardScaler*.  

---

## 📊 Visualization
Some of the visualizations include:
- *Boxplots* of Sepal & Petal dimensions by species  
- *Pairplot* for multivariate feature relationships  
- *Correlation Heatmap*  

Example Pairplot:  
```python
sns.pairplot(iris, hue="Species")
plt.show()
