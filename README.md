# SVM Classification on Iris Dataset

## Project Overview
This project demonstrates the use of Support Vector Machines (SVM) for classifying the Iris dataset. The objective is to compare the performance of different SVM kernels (linear, polynomial, and RBF) and analyze how they handle complex decision boundaries.

---

## Dataset
- **Name:** Iris Dataset  
- **Source:** UCI Machine Learning Repository  
- **Description:** The dataset contains 150 samples of iris flowers classified into three species: setosa, versicolor, and virginica. Each sample has four features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)  

---

## Objectives
1. Load and explore the Iris dataset.
2. Train and evaluate SVM models with different kernels:
   - Linear
   - Polynomial (degree = 3)
   - RBF (Radial Basis Function)
3. Compare model performance using:
   - Accuracy
   - Precision, Recall, and F1-Score (Classification Report)
   - Confusion Matrix
4. Visualize and interpret the results.

---

## Installation and Setup
### 1. Install Dependencies:
Make sure you have Python 3.x installed. Install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
