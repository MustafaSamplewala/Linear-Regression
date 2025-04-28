# Linear-Regression

## 📋 Task Overview
This project implements **Simple and Multiple Linear Regression** models on a housing dataset to predict house prices.

**Objective:**  
- Learn and apply Linear Regression using `scikit-learn`.
- Understand preprocessing, model fitting, evaluation metrics, and coefficient interpretation.

---

## 🛠️ Tools Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**

---

## 📂 Dataset
The dataset used is [`Housing.csv`], containing features like:
- Area
- Bedrooms
- Bathrooms
- Parking
- Furnishing Status
- ...and more.

**Target Variable:**  
- `price` (House Price)

---

## 🔥 What I Did
- Imported the dataset and handled missing values (if any).
- Encoded categorical features using **One-Hot Encoding** (`pd.get_dummies()`).
- Split the dataset into **training** and **testing** sets.
- Trained a **Linear Regression** model.
- Evaluated the model using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**
- Interpreted the model coefficients.
- Plotted a regression line using the `area` feature for visualization (Simple Linear Regression).

---

## 📊 Results
- Achieved a good R² Score on the test data.
- Observed that features like **area** have a strong positive correlation with price.
- Successfully handled categorical variables (like `furnishingstatus`) for model compatibility.

---

## 📊 Evaluation Metrics Example
| Metric | Value |
|:------:|:-----:|
| MAE    | ~ value |
| MSE    | ~ value |
| R²     | ~ value |

(Values will depend on your actual model outputs.)

## 🚀 Final Note
This project helped strengthen my understanding of Regression Modeling, Data Preprocessing, and Model Evaluation techniques!

