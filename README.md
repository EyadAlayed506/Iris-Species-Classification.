# **Iris Flower Classification: A Comparative Machine Learning Study**

This repository contains a comprehensive data science project that classifies iris flower species using seven different machine learning algorithms. The project benchmarks traditional statistical models against modern gradient-boosting techniques using robust 5-fold cross-validation.

## **📊 Project Overview**

The goal of this project is to predict the species of an iris flower (**Setosa, Versicolor, or Virginica**) based on its sepal and petal measurements.

### **Key Features:**

* **Comprehensive EDA**: Analysis of class balance and data integrity.  
* **Data Preprocessing**: Implementation of LabelEncoder, duplicate removal, and StandardScaler for feature normalization.  
* **Advanced Validation**: Used KFold (5 folds) to ensure model results are consistent and not biased by a single train-test split.  
* **Performance Comparison**: Comparison of 7 models across multiple metrics: Accuracy, Precision, Recall, and F1-Score.

## **🛠️ Tech Stack**

* **Languages**: Python  
* **Libraries**:  
  * Data Manipulation: Pandas, NumPy  
  * Visualization: Matplotlib, Seaborn  
  * Machine Learning: Scikit-learn, XGBoost, CatBoost  
* **Dataset Source**: [Iris Flower Dataset via Kaggle](https://www.kaggle.com/arshid/iris-flower-dataset)

## **🏆 Model Performance & Results**

Below are the average results across the 5-fold cross-validation:

| Model | Accuracy | F1-Score | Precision | Recall |
| :---- | :---- | :---- | :---- | :---- |
| **SVM (RBF Kernel)** | **0.9662** | **0.9663** | **0.9682** | **0.9662** |
| Logistic Regression | 0.9591 | 0.9591 | 0.9643 | 0.9591 |
| XGBoost | 0.9526 | 0.9524 | 0.9554 | 0.9526 |
| Random Forest | 0.9524 | 0.9525 | 0.9570 | 0.9524 |
| CatBoost | 0.9455 | 0.9454 | 0.9526 | 0.9455 |
| KNN | 0.9455 | 0.9457 | 0.9511 | 0.9455 |
| Decision Tree | 0.9320 | 0.9320 | 0.9381 | 0.9320 |

**Conclusion**: The **Support Vector Machine (SVM)** model outperformed all other classifiers with an accuracy of **96.62%**, making it the most robust choice for this specific classification task.
