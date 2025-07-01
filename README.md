# Linear-Regression-on-housing-dataset
A clean implementation of simple linear regression on a housing dataset. The model is trained to predict house prices from square footage using visualization, model training, and evaluation techniques.

# 🏠 Simple Linear Regression - Real Estate Dataset

This project demonstrates the use of **Simple Linear Regression** to predict **house prices** based on the **size of the house** (in square feet). The dataset is small and ideal for educational purposes.

---

## 📊 Dataset Summary

The dataset contains the following fields:

- `Size_sqft`: Area of the house in square feet
- `Price`: Price of the house (in INR/USD)

---

## 🔍 Objective

To build a predictive model using **Simple Linear Regression** that estimates the price of a house based on its size.

---

## ⚙️ Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🧠 Project Workflow

1. **Data Import**  
   Load the dataset from a `.csv` file.

2. **Exploratory Data Analysis (EDA)**  
   - Visualize the relationship between size and price
   - Check for correlation

3. **Model Building**  
   - Use `LinearRegression()` from `sklearn.linear_model`
   - Fit model on training data

4. **Model Evaluation**  
   - Predict values
   - Calculate R² score, Mean Squared Error (MSE)

5. **Visualization**  
   - Plot regression line with actual data

---

## 📁 Files Included

├── simple_Reg_realEstate_dataset.ipynb # Jupyter notebook with full code
├── real_estate_dataset.csv # Dataset used for regression
└── README.md # Project documentation

## 📈 Output

The project outputs a simple but effective regression line that estimates house price based on size, helping you understand how to build and interpret linear models in real-world scenarios.
