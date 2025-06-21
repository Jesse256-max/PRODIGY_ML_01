# 🏡 House Price Prediction using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on:
- Square footage (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of bathrooms (`FullBath`)

The dataset used is from the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## 📁 Dataset

The data is taken from the `train.csv` file available on Kaggle.  
Make sure to place the dataset in the same directory as your script or notebook.

## 📌 Features Used

| Feature        | Description                               |
|----------------|-------------------------------------------|
| `GrLivArea`    | Above ground living area (square feet)    |
| `BedroomAbvGr` | Number of bedrooms above ground           |
| `FullBath`     | Number of full bathrooms                  |

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🧠 Model

We use **Linear Regression** to learn a relationship between the selected features and the target variable `SalePrice`.

### Steps:
1. Data loading and feature selection
2. Data cleaning and preprocessing
3. Train/test split
4. Model training using `LinearRegression`
5. Evaluation (MSE, R² Score)
6. Visualization of predictions

## 📊 Output Metrics

After training the model, the following metrics are printed:

- **Mean Squared Error (MSE)**
- **R-squared Score**
- **Model Coefficients & Intercept**

A scatter plot is also generated comparing **Actual vs Predicted** house prices.

## ▶️ How to Run

1. Install required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn


## Access The Project
https://github.com/Jesse256-max/PRODIGY_ML_01.git
