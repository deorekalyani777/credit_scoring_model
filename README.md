# Credit Scoring Model

## 📌 Project Overview

This project predicts an individual's creditworthiness using historical financial data and Machine Learning classification algorithms.

The project was developed as part of an internship task.

## 🎯 Objective

The main objective is to classify customers into:

- Good Credit
- Bad Credit

based on their financial and personal information.

## 📊 Dataset

The project uses the **German Credit Dataset** from the UCI Machine Learning Repository.

Dataset contains:

- 1000 customer records
- 20 input features
- 1 target variable

## 🤖 Machine Learning Algorithms

Three classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## 🔄 Project Workflow

1. Dataset Collection
2. Data Loading
3. Data Understanding
4. Data Preprocessing
5. Categorical Feature Encoding
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Prediction
10. Model Evaluation
11. Model Comparison
12. Best Model Selection
13. Model Saving
14. New Customer Prediction

## 🧪 Sample Prediction

The trained model was tested on a new customer.

The model predicted:

**Good Credit**

with a probability of approximately **66%** for the sample customer.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib
- VS Code

## 📁 Project Structure

```text
CREDIT_SCORING_MODEL/
│
├── dataset/
│   └── german.data
│
├── graphs/
│   ├── model_comparison.png
│   ├── feature_importance.png
│   ├── roc_curve.png
│   └── final_model_results.csv
│
├── model/
│   ├── best_credit_model.pkl
│   ├── scaler.pkl
│   └── feature_columns.pkl
│
├── notebook2/
│   └── credit_scoring_model.ipynb
│
├── venv/
│
└── README.md

## 🔮 Future Improvements

The following improvements can be made in the future:

1. **Hyperparameter Tuning**  
   Optimize the machine learning models to improve prediction performance.

2. **Web Application**  
   Develop a user-friendly web interface where users can enter their details and get a credit prediction.

3. **Real-Time Prediction**  
   Integrate the trained model into a real-time credit scoring system.

4. **Model Deployment**  
   Deploy the model using platforms such as Streamlit, Flask, or cloud services.

5. **Larger Dataset**  
   Train the model using a larger and more diverse dataset to improve reliability.

6. **Advanced Machine Learning Models**  
   Experiment with algorithms such as XGBoost and Gradient Boosting.

7. **Explainable AI**  
   Add explainability techniques to show why a customer was classified as Good Credit or Bad Credit.

👩‍💻 Author
Kalyani Deore
Computer Engineering Student
SPPU