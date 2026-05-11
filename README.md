# MA289-Project-3-Comparative-Analysis-of-Data-Standardization-Techniques
Comparative analysis of feature standardization techniques using KNN classification on synthetic and real-world datasets.

# Comparative Analysis of Data Standardization Techniques

## Overview

This project goes through standardization/scaling and its different types. It shows how the method affects the performance of K-Nearest Neighbors (KNN) classification. The project compares:

- No Scaling
- StandardScaler (Typical standardization or Z-Score Standardization)
- MinMaxScaler
- RobustScaler

The methods are tested using:
1. Synthetic datasets to show the underlying basics.
2. The "Estimation of Obesity Levels Based On Eating Habits and Physical Condition" dataset to show a real-world application.

The goal of the project is to see the benefits of standardization and the best use cases for each of the types. Additionally, it shows how and why different scaling techniques behave differently.

---

## Project Objectives

- Explanation of Standardization/Scaling
- Description and mathematical formulation of the types of standardization
- Show how distance-based models are affected
- Compare standardization techniques on synthetic and real world datasets
- Evaluate scaling performance using KNN classification accuracy

---

## Dataset

### Real-World Dataset
- Estimation of Obesity Levels Based On Eating Habits and Physical Condition

### Target Variable
The original obesity categories were simplified into a binary classification problem:
- Obese
- Not Obese

### Note
The `Weight` feature was intentionally removed because it acts as a proxy for obesity and would dominate the prediction task.

---

## Methods Used

### Machine Learning Model
- K-Nearest Neighbors (KNN)

### Scaling Methods
- StandardScaler
- MinMaxScaler
- RobustScaler

### Evaluation Metric
- Classification Accuracy

---

## Repository Structure

```text
project3-standardization/
│
├── notebooks/
├── data/
├── report/
├── README.md
```

---

## Running the Project

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Python Scripts

```bash
python code/knn_standardization.py
```

---

## Visualizations Included

- Accuracy comparison bar graphs
- Standardization movement visualizations
- Synthetic dataset comparisons
- Scaling transformation plots

---

## Key Findings

- KNN performance improves significantly after standardization
- StandardScaler performed best on the obesity dataset
- MinMaxScaler was more sensitive to outliers
- RobustScaler performed well but had limited advantages due to the dataset containing relatively few extreme outliers

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Author

Massimo Sincavage

MA289 - Mathematics of AI
