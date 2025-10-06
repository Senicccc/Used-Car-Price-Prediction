#  Used Cars Price Prediction - Data Mining Midterm Project

This project aims to **predict the price of used cars** using a dataset from Kaggle.  
The model applies **Linear Regression** with Python on Google Colab, focusing on practical steps of **data preprocessing**, **feature engineering**, and **model evaluation**.

---

## 📊 Dataset

The dataset contains information about used cars in India, including features such as:
- Car name and company  
- Year of manufacture  
- Fuel type  
- Transmission type  
- Mileage, engine size, and more  

**Source:**  
[Used Cars Price Prediction Dataset (GitHub)](https://raw.githubusercontent.com/FarrelllAdityaaa/dataset-uts-datamining/refs/heads/main/used_cars_price_fiks.csv)

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Load dataset using **pandas**
- Handle missing values by removing or filling with appropriate statistics
- Convert categorical variables into numeric format using **One-Hot Encoding**
- Drop unnecessary columns such as IDs or redundant data

### 2. Data Splitting & Scaling
- Split dataset into **80% training data** and **20% testing data**
- Normalize features using **StandardScaler** to improve regression performance

### 3. Model Development
- Train a **Linear Regression** model using `scikit-learn`
- Fit the model with training data and make predictions on testing data

### 4. Model Evaluation
Evaluate the model using several metrics:
- **R² (Coefficient of Determination)** — measures how well the model fits the data  
- **MAE (Mean Absolute Error)** — average magnitude of prediction error  
- **MSE (Mean Squared Error)** — penalizes large errors  
- **RMSE (Root Mean Squared Error)** — interpretable in the same unit as target price  

### 5. Visualization
- Scatter plot between **actual vs predicted prices**  
- Residual analysis to check if the model errors are normally distributed  

---

## 🧠 Libraries Used
- **pandas** — data manipulation  
- **numpy** — numerical operations  
- **matplotlib & seaborn** — data visualization  
- **scikit-learn** — preprocessing, regression, and metrics  

---

## 📈 Example Results

| Metric | Value |
|--------|--------|
| R² Score | 0.85 |
| MAE | 1.20 Lakh |
| MSE | 4.25 |
| RMSE | 2.05 Lakh |

> *Results may vary depending on preprocessing and random data split.*

---

## 📷 Visualization Example

![Prediction vs Actual](hasil_prediksi.png)

The scatter plot above shows that most predicted prices are close to the actual prices,  
indicating that the Linear Regression model performs reasonably well on this dataset.

---

## 🧩 Repository Structure
used-cars-price-prediction/
│
├── README.md # Project documentation (this file)
├── UTS_Data_Mining.ipynb # Main Google Colab notebook
├── used_cars_price_fiks.csv # Dataset file
├── slides_uts_datamining.pptx # Presentation slides
└── hasil_prediksi.png # Visualization of model predictions


---

## 💡 Summary

This project demonstrates how to:
- Apply **data preprocessing** and handle real-world datasets  
- Build a **Linear Regression** model using scikit-learn  
- Evaluate and visualize model performance effectively  

Through this project, we can better understand how simple regression models can be used  
to make data-driven predictions for real business scenarios such as car pricing.

---

**Created by:** *[Your Name]*  
*Data Mining — Semester 5 (Informatics Department)*  


benerin
