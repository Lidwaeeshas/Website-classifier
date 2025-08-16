# Website Category Classification

**A machine learning project that classifies websites into categories based on their textual content using Python, TF-IDF vectorization, and Logistic Regression.**

## 📝 Project Overview

This project demonstrates a complete text classification pipeline:  

- **Text preprocessing** and cleaning  
- **Feature extraction** with TF-IDF  
- **Label encoding** for categorical targets  
- **Model selection and hyperparameter tuning** using `GridSearchCV`  
- **Evaluation** with accuracy, precision, recall, F1-score, and confusion matrix  

The model predicts the category of a website based on its content, useful for content organization, search optimization, and automated website tagging.

---

## ⚙️ Technologies & Libraries

- **Python 3.x**  
- **pandas** – for data manipulation  
- **numpy** – for numerical operations  
- **scikit-learn** – for machine learning, TF-IDF, model building, and evaluation  

---

## 🚀 Features

- Multinomial Logistic Regression with balanced class weights  
- Hyperparameter tuning with `GridSearchCV`  
- Stratified train-test split for balanced evaluation  
- Weighted metrics to handle class imbalance  

---

## 📊 Performance Metrics

| Metric     | Score |
|-----------|-------|
| Accuracy  | 0.9314 |
| Precision | 0.9326 |
| Recall    | 0.9314 |
| F1-Score  | 0.9314 |

**Confusion Matrix:**
[[ 3  0  0  0  0  0  0  0  1  0  0  0  1  0  0  0]
 [ 0 28  3  1  1  0  0  0  0  0  0  0  0  0  0  0]
 [ 0  1 27  0  0  0  0  0  0  0  0  0  0  0  0  0]
 [ 1  1  0 29  0  0  0  0  0  0  0  0  0  0  0  0]
 [ 0  0  1  0 33  0  0  0  0  0  0  0  0  0  0  0]
 [ 0  0  0  0  0 27  0  0  0  0  0  0  0  1  0  0]
 [ 0  1  0  0  0  0  2  0  0  0  2  0  0  0  0  0]
 [ 0  0  1  0  0  0  0 27  0  0  0  0  1  0  0  0]
 [ 0  1  0  0  0  2  0  0 26  0  0  0  0  0  0  0]
 [ 0  0  0  0  0  0  0  0  0 25  0  0  0  0  0  0]
 [ 0  0  0  0  0  0  1  0  0  0 27  0  0  1  0  0]
 [ 0  0  0  0  0  0  0  0  0  0  0 28  0  0  0  0]
 [ 0  1  1  0  0  1  0  0  0  0  1  1 20  0  0  0]
 [ 0  0  0  0  0  0  0  0  0  0  1  0  0 30  0  0]
 [ 0  0  1  0  0  0  0  0  0  0  0  0  0  0 30  0]
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 32]]
