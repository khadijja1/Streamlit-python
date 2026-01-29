# 🍄 Interactive Mushroom Classification Web App (Streamlit)


## Project Overview
This project delivers an end-to-end Machine Learning solution for classifying mushrooms as edible or poisonous. It is deployed as an interactive web application using **Streamlit**, allowing users to select a classification model (SVM, Logistic Regression, or Random Forest) and tune its hyperparameters in real-time. This demonstrates a complete **MLOps workflow** from model training to interactive deployment.

## ✨ Key Features
*   **Interactive UI:** Built with Streamlit, providing a user-friendly interface for model selection and parameter tuning.
*   **Multiple Model Comparison:** Allows real-time comparison of three distinct classification algorithms: Support Vector Machine (SVM), Logistic Regression, and Random Forest.
*   **Dynamic Performance Metrics:** Visualizes key performance indicators, including **Confusion Matrix**, **ROC Curve**, and **Precision-Recall Curve**, which update dynamically based on the selected model and hyperparameters.
*   **High Accuracy:** The best-performing model (Random Forest) achieved an accuracy of **~99.8%** on the test set, demonstrating robust classification performance.

## 🛠️ Technologies Used
*   Python
*   Streamlit (for web deployment)
*   Scikit-learn (for model training and metrics)
*   Pandas, NumPy

## How to Run Locally
1.  Clone the repository: `git clone https://github.com/YourUsername/streamlit-mushroom-classifier.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the app: `streamlit run app.py`
