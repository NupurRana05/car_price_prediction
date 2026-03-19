# Car Price Prediction using Machine Learning

##  Project Overview
This project predicts the price of used cars using Machine Learning techniques. It uses **Linear Regression** to estimate car prices based on features like company, model, year, fuel type, and kilometers driven.

An interactive web interface is built using **Streamlit**, allowing users to input car details and get real-time price predictions.

---

##  Features
- Data cleaning and preprocessing of raw dataset
- Feature engineering (handling categorical + numerical data)
- Machine Learning model using Linear Regression
- Pipeline implementation using Scikit-learn
- OneHotEncoding for categorical variables
- Interactive UI using Streamlit
- Model saved using Pickle for fast loading

---

##  Tech Stack
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit

---

##  Dataset
- Dataset contains car details such as:
  - Name
  - Company
  - Year
  - Price
  - Kilometers Driven
  - Fuel Type

---

##  Data Preprocessing Steps
- Removed invalid and missing values
- Cleaned `year`, `Price`, and `kms_driven` columns
- Converted data types (string → numeric)
- Handled outliers in price
- Extracted meaningful car names

---

## 🤖 Model Building
- Used **Linear Regression**
- Applied **OneHotEncoder** for categorical features
- Created pipeline using `ColumnTransformer`
- Evaluated using **R² Score**

---

##  Streamlit Web App
The project includes an interactive UI where users can:
- Select car company
- Enter car name
- Choose fuel type
- Enter year and kilometers driven
- Get predicted car price instantly

---
