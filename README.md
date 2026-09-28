🏠 House Price Prediction — Machine Learning Task 2

📌 Project Overview

This project builds a Machine Learning regression model to predict house prices.

The project follows a complete Machine Learning workflow:

- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Handling zero-price records
- Categorical encoding
- Log transformation
- Feature scaling
- Model training
- Model comparison
- Model evaluation
- Residual analysis
- House price prediction
- Model saving and loading

---

🎯 Objective

The main objective is to predict house prices using housing features and compare different regression models.

---

📊 Dataset

The dataset contains 4,600 records and 18 original columns.

After removing 49 records with zero house prices, the final dataset contains:

- 4,551 records
- 18 original columns

Target Variable

"price"

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab / Jupyter Notebook

---

🔧 Feature Engineering

The following transformations were performed:

- Extracted "sale_year" from date
- Extracted "sale_month" from date
- Created "total_sqft"
- Created "house_age"
- Removed the original "date" column
- Removed "street" and "country"
- One-hot encoded "city" and "statezip"
- Applied log transformation to price and selected numerical features
- Applied feature scaling

---

🤖 Machine Learning Models

Three regression models were trained and compared:

1. Linear Regression
2. Random Forest
3. Gradient Boosting

Model Results

Model| RMSE| MAE
Linear Regression| 0.257282| 0.154907
Gradient Boosting| 0.285705| 0.195852
Random Forest| 0.287697| 0.187354

---

📈 Evaluation

The models were evaluated using:

- RMSE — Root Mean Squared Error
- MAE — Mean Absolute Error

Residual analysis and Actual vs Predicted analysis were also performed.

---

🔮 Sample Prediction

A sample house price prediction was demonstrated in the notebook.

Example prediction:

$311,501.90

---

💾 Saved Model Files

The following files are included in this repository:

house_price_model.pkl
house_price_scaler.pkl
requirements.txt

Model

"house_price_model.pkl" contains the trained machine learning model.

Scaler

"house_price_scaler.pkl" contains the feature scaling object required for preprocessing prediction data.

---

▶️ How to Run the Project

1. Install required libraries

pip install -r requirements.txt

2. Open the notebook

Open:

House_Price_Prediction_Task_2.ipynb

using Google Colab or Jupyter Notebook.

3. Run the notebook

Run the cells from top to bottom to reproduce the preprocessing, training, evaluation and prediction workflow.

---

🔗 Project Links

Google Colab Notebook

https://colab.research.google.com/drive/1Zndt7b4kOB28QUYiS-XVZ6sx0r2YMHzP?usp=sharing

GitHub Repository

https://github.com/RushikeshGame/House-Price-Prediction

---

📁 Project Structure

House-Price-Prediction/
│
├── House_Price_Prediction_Task_2.ipynb
├── house_price_model.pkl
├── house_price_scaler.pkl
├── requirements.txt
├── README.md
└── House_Price_Prediction_Task_2_Updated.pdf

---

👨‍💻 Project

Machine Learning Internship — Task 2

Project: House Price Prediction
