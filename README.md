# Experiment 3: Feature Engineering

This experiment focuses on discussing concepts and techniques used for **feature engineering**, a crucial step in preparing data for machine learning and analysis. Exercises are included to apply the concepts and develop essential practical skills.

---

## Topics Covered

### 1️ Data Transformation
Data transformation is a key step in preprocessing raw data to make it suitable for machine learning models. Techniques include:

- **Scaling:** Transform numerical features to a common scale without changing their relative relationships.  
  - Min-Max scaling: scales features to a specific range (e.g., [0, 1])  
  - Standardization: transforms features to have zero mean and unit variance  

- **Discretization:** Converts continuous numerical data into discrete categories or bins.  
  - Equal-width binning: divides data into intervals of equal width  
  - Equal-frequency binning: ensures each bin has approximately the same number of data points  

- **Encoding:** Converts categorical data into numerical format that models can understand.  
  - One-hot encoding: creates binary columns for each category  
  - Label encoding: assigns a unique integer to each category  
  - Ordinal encoding: maps ordinal categories to numerical values  

---

### 2️ Handling High-Dimensional Data
High-dimensional data can complicate analysis and modeling. Techniques include:

- **Principal Component Analysis (PCA):** Reduces the number of features while preserving as much variance as possible, simplifying data without losing important information.  

---

## Objective
- Learn key feature engineering techniques including scaling, discretization, encoding, and dimensionality reduction.  
- Apply these methods to prepare datasets for machine learning and analysis.  

---

## Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Numpy  

