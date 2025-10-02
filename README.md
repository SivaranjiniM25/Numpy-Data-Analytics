# Numpy-Data-Analytics
## 🍷 Wine Quality Data Analytics using NumPy

## 📌 Project Overview

This project analyzes the **Red and White Wine Quality datasets** using **NumPy**. The goal is to perform exploratory data analysis and demonstrate NumPy operations such as aggregation, filtering, reshaping, sorting, and combining datasets.

## 📂 Dataset Description

The datasets are sourced from **Kaggle (Wine Quality Dataset)**.
Each record includes physicochemical test results (input variables) and a quality score (output variable).

### 🔹 Input Variables (features)

1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

### 🔹 Output Variable

12. Quality (score between 0 and 10, based on sensory data)

👉 Both **red wines** and **white wines** datasets follow the same structure.

## ⚙️ NumPy Skills Demonstrated

* Reading datasets with `np.genfromtxt()`
* Data slicing and indexing
* Aggregations (`sum`, `mean`, `max`, `min`, `percentile`)
* Conditional filtering (e.g., wines with quality > 7)
* Reshaping and flattening arrays
* Combining red & white wine datasets (`vstack`, `concatenate`)
* Sorting values with `np.argsort()`
