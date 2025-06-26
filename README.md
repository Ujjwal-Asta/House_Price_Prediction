# 🏠 House Price Prediction using Linear Regression

This project is part of the *AI & ML Internship (Task 3)* offered by *Elevate Labs. It involves building a predictive model using **Multiple Linear Regression* to estimate housing prices based on various features.

---

## 📊 Project Overview

The objective of this project is to implement and evaluate a *Multiple Linear Regression* model on a housing dataset. The model predicts the *price of a house* based on multiple features such as area, number of bedrooms, bathrooms, and furnishing status.

---

## 🗂 Dataset

The dataset used in this project is Housing.csv, which contains various attributes of residential properties, including:

- price — Price of the house (Target variable)
- area — Area in square feet
- bedrooms — Number of bedrooms
- bathrooms — Number of bathrooms
- stories — Number of floors
- mainroad, guestroom, basement, hotwaterheating, airconditioning, furnishingstatus — Categorical features

---

## 🛠 Technologies & Libraries Used

- *Python 3*
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Scikit-learn](https://scikit-learn.org/)

---

## 🔧 Methodology

### 1. Data Preprocessing
- Loaded the dataset using pandas
- Handled missing values
- Converted categorical variables into numeric using one-hot encoding

### 2. Model Building
- Split data into training and test sets (80/20 split)
- Trained a *Linear Regression* model using scikit-learn

### 3. Model Evaluation
- Predicted prices on the test set
- Evaluated performance using:
  - *Mean Absolute Error (MAE)*
  - *Mean Squared Error (MSE)*
  - *R² Score*

### 4. Visualization
- Created a scatter plot comparing actual vs predicted prices

---

## 📈 Results

The model's performance was evaluated on test data. Example metrics:

- *MAE:* e.g., 122000
- *MSE:* e.g., 27300000000
- *R² Score:* e.g., 0.68

*Note:* These values will vary depending on your actual model run.

---

## 📌 How to Run

1. Clone the repository or download the files  
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas scikit-learn matplotlib

3. Run the script:

python linear_regression.py




---

📂 Folder Structure

Linear_Regression_Task/
├── Housing.csv
├── linear_regression.py
└── README.md


---

🚀 Future Improvements

Feature selection and scaling

Experiment with other models (Ridge, Lasso)

Web app using Streamlit or Flask



---

👨‍💻 Author

Ujjwal Mishra
AI & ML Intern — Elevate Labs
GitHub Profile - https://github.com/Ujjwal-Asta


---
