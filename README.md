# 📊 User Retention Prediction System

## 📌 Project Overview

This project aims to predict user retention using machine learning techniques based on application data from the Google Play Store.

Since direct user activity data is not available, app-level engagement metrics such as installs, ratings, and user interactions are used as proxies for user behavior.

The objective is to identify whether an application is likely to retain users and provide insights to improve retention strategies.

---

## 🎯 Objectives

* Predict user retention using machine learning models
* Analyze factors influencing retention
* Provide actionable business insights
* Evaluate model performance using multiple metrics

---

## 🧠 Models Used

The following models were implemented:

* Logistic Regression
* Random Forest
* Gradient Boosting

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Confusion Matrix
* ROC-AUC Score
* Classification Report (Precision, Recall, F1-score)
* Cross-validation

---

## 📈 Key Features

* Data preprocessing and cleaning
* Feature engineering (engagement and popularity metrics)
* Handling class imbalance
* Feature importance analysis
* Visualization (ROC curve, confusion matrix, etc.)

---

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle:

👉 https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

⚠️ **Note:**
The dataset is not included in this repository due to its large size.

---

## ⚙️ How to Run the Project

1. Download the dataset from Kaggle
2. Place the CSV file in the project directory
3. Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 🧠 Key Insights

* User engagement is the strongest driver of retention
* Popular apps retain users more effectively
* In-app purchases indicate stronger user commitment
* Regular updates improve retention
* App category has less impact compared to user behavior

---

## 🚀 Results

* High model performance across all metrics
* Strong ability to distinguish retained vs non-retained apps
* Tree-based models (Random Forest, Gradient Boosting) performed best

---

## ⚠️ Limitations

* Retention is approximated using proxy variables
* Dataset is highly imbalanced
* No direct user-level behavioral data

---

## 🔮 Future Work

* Use real user activity data (sessions, time spent)
* Apply hyperparameter tuning
* Explore additional models
* Incorporate time-series analysis

---

## 👩‍💻 Author

JEMIMA KOKOBE

---

## 📌 Note for Evaluators

This project was developed as part of an academic assignment.
All preprocessing, modeling, and evaluation steps are included in the code.

Please download the dataset from the link above before running the project.
