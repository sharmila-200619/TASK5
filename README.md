# TASK5
DECISION TREE TREES AND RANDOM FORESTS
# 🎯 Decision Tree vs Random Forest: A Classification Project

This project demonstrates the use of *Decision Trees* and *Random Forests* on a binary classification dataset (such as Titanic or Breast Cancer), including visualization, overfitting analysis, feature importance, and evaluation using cross-validation.

---

## 📌 Objectives

1. *Train a Decision Tree Classifier* and visualize it.
2. *Analyze overfitting* by tuning the tree depth.
3. *Train a Random Forest Classifier* and compare performance.
4. *Interpret feature importances* from the Random Forest.
5. *Evaluate both models using cross-validation.*

---

## 🗂️ Folder Structure

project/ │ ├── decision_tree_visualization.ipynb     # All 5 tasks implemented in separate cells ├── README.md                             # This file ├── titanic.csv (optional)                # Use your own or fetch via Seaborn/Kaggle

---

## 📊 Dataset Options

You can use either of the following binary classification datasets:

### 1. 🩺 Breast Cancer (sklearn built-in)
- ✅ No download required
- Features: radius, texture, perimeter, area, etc.
- Target: 0 = malignant, 1 = benign

### 2. 🚢 Titanic Dataset
- Requires preprocessing (handle missing values, encode categorical)
- Target: 0 = Did not survive, 1 = Survived
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## ⚙️ Tools & Libraries Used

- Python 3
- scikit-learn
- pandas
- matplotlib
- numpy

Make sure all are available in your environment (Colab or Jupyter supports them by default).

---

## ✅ Task Breakdown

### Task 1 – Train a Decision Tree & Visualize
- Load dataset
- Train DecisionTreeClassifier
- Visualize the tree using plot_tree
- Measure accuracy on training and test sets

### Task 2 – Analyze Overfitting with Tree Depth
- Vary max_depth from 1 to 10
- Plot accuracy on training vs test data
- Find optimal depth

### Task 3 – Train a Random Forest
- Train RandomForestClassifier using best depth
- Compare accuracy with decision tree

### Task 4 – Interpret Feature Importances
- Plot top 10 most important features
- Understand which features drive predictions

### Task 5 – Cross-Validation Evaluation
- Perform 5-fold cross-validation
- Compare average accuracy & standard deviation of both models

---

## 🚀 How to Run

1. Open the .ipynb file in *Google Colab* or *Jupyter Notebook*.
2. Run each code cell from top to bottom.
3. Review graphs and accuracy outputs.
4. Modify dataset or model settings as needed.

---

## 📈 Sample Outputs

- Tree Visualization
- Depth vs Accuracy Graph
- Feature Importance Bar Chart
- CV Accuracy Metrics Table

---

## 📬 Author

*Sharmila L.*  
Machine Learning Project – June 2025
