# Customer Churn Prediction using Gradient Boosting

This repository contains a machine learning solution for predicting customer churn using Gradient Boosting. The solution is implemented as part of the **CodSoft Internship**.

## 📌 Project Overview
Customer churn is a crucial metric for businesses to understand customer retention. This project leverages machine learning to predict whether a customer will churn based on various features from a dataset.

## 📂 Dataset
The dataset used is **Churn_Modelling.csv**, which includes customer details such as Geography, Gender, Age, Balance, Credit Score, and more. The target variable is `Exited`, where:
- `0` indicates the customer did not churn.
- `1` indicates the customer churned.

## 🛠️ Steps Involved
1. **Load the Data**: Read the dataset and explore its structure.
2. **Data Preprocessing**:
   - Dropped unnecessary columns (`RowNumber`, `CustomerId`, `Surname`).
   - Encoded categorical variables (`Geography`, `Gender`).
   - Standardized numerical features using `StandardScaler`.
   - Split the data into training and testing sets.
3. **Train a Gradient Boosting Model**:
   - Used `GradientBoostingClassifier` with 100 estimators, learning rate of 0.1, and max depth of 3.
4. **Evaluate the Model**:
   - Computed accuracy score and classification report.
   - Plotted a confusion matrix for visualization.

## 🚀 How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-churn-prediction
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
4. Run the script:
   ```bash
   python churn_prediction.py
   ```

## 📊 Model Performance
The model achieves a competitive accuracy score and provides a detailed classification report. The confusion matrix helps in visualizing the model’s predictions.

## 🤝 Contributing
Feel free to fork this repository, improve the model, or experiment with hyperparameters. Pull requests are welcome!

---
### 🔗 Connect
For any queries, feel free to reach out on GitHub or LinkedIn!



