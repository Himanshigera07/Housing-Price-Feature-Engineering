
# 🏠 Housing Price Feature Engineering

This project demonstrates feature engineering techniques on a housing price dataset using Python and Scikit-learn. The notebook includes steps for handling missing data, encoding categorical variables, scaling numeric features, and creating meaningful new features.

---

## 📋 Dataset Overview

The dataset contains columns such as:
- `area`
- `location`
- `bedrooms`
- `bathrooms`
- `price`

---

## 🔧 Steps Performed

### 1. Handle Missing Values
- Used `SimpleImputer` to fill missing numeric and categorical values.

### 2. Encode Categorical Features
- Applied one-hot encoding using `OneHotEncoder` to convert categorical data to numeric.

### 3. Normalize Numerical Features
- Used `MinMaxScaler` to scale numerical columns between 0 and 1.

### 4. Feature Engineering
Created two new features:
- `price_per_sqft` = `price / area`
- `total_rooms` = `bedrooms + bathrooms`

These new features aim to capture more meaningful signals for downstream modeling.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 💻 How to Use

1. Clone this repository or download the notebook.
2. Open `Task_2_Enhanced.ipynb` in Jupyter Notebook or any compatible environment.
3. Run the cells step by step to explore the feature engineering process.

---

## 📌 Author

**Himanshi Gera**  
[LinkedIn] (www.linkedin.com/in/himanshi-gera-b15558278)
---
