# Credit Scoring Model Using Machine Learning

## 📌 Project Overview

This project is developed as part of the **CodeAlpha Machine Learning Internship**. The objective is to build a machine learning model that predicts whether a customer has **Good Credit** or **Bad Credit** based on historical financial information.

The project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and model saving.

---

## 🎯 Objective

Develop a classification model to predict an individual's creditworthiness using financial and personal attributes.

---

## 📂 Dataset

* Dataset: German Credit Data
* Number of Records: 1000
* Number of Features: 20
* Target Variable: `target`

  * Good Credit
  * Bad Credit

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## 🤖 Machine Learning Algorithms

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Among these, **Random Forest** achieved the best performance and was selected as the final model.

---

## 📊 Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## 📈 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Preprocessing
5. Encode Categorical Variables
6. Split Dataset into Training and Testing Sets
7. Train Multiple Machine Learning Models
8. Compare Model Performance
9. Evaluate Final Model
10. Save Trained Model using Joblib

---

## 📁 Project Structure

```text
CodeAlpha_CreditScoringModel/
│── Credit_Scoring_Model.ipynb
│── german_credit_data.csv
│── credit_scoring_model.pkl
│── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Upload the dataset (`german_credit_data.csv`).
3. Run all notebook cells.
4. Train the models.
5. Evaluate the results.
6. Save the trained model.

---

## 📌 Results

* Successfully trained multiple classification models.
* Compared model performance.
* Selected the best-performing model.
* Saved the trained model as `credit_scoring_model.pkl`.

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Feature Engineering
* Cross Validation
* Streamlit Web Application
* Deployment using Flask or FastAPI

---

## 👨‍💻 Author

**Aditya Ghatage**

B.Tech – Artificial Intelligence & Machine Learning

CodeAlpha Machine Learning Internship

---

## ⭐ Acknowledgements

* CodeAlpha
* Scikit-learn
* Google Colab
* German Credit Dataset
