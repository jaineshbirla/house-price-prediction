# house-price-prediction
# Irish House Rent Prediction (Machine Learning Project)

## 📌 Project Description

This project focuses on predicting house rent prices in Ireland using machine learning techniques. The dataset is taken from Kaggle and contains structured information related to time, location, and property characteristics. The goal is to build a reliable regression model that can learn patterns from historical data and predict rent values accurately.

This project is built as an academic ML project suitable for:

* Internships
* Interviews
* GitHub portfolio
* Academic evaluation

---

## 📂 Dataset

**Source:** Kaggle (Irish Rent Dataset)

### Target Variable:

* `rent_euro` → House rent in euros

### Input Features (after preprocessing):

* `year`
* `half`
* `time_period`
* `county`
* `province`
* `area`
* `property_type`
* `bedrooms`
* `is_dublin`
* `is_city`
* `is_county_aggregate`

---

## 🧹 Data Preprocessing

The following steps were applied:

* Removal of redundant/composite features (`half_year`, `location`)
* Handling missing values
* Feature selection based on redundancy checks
* Encoding of categorical variables
* Logical feature dropping based on EDA

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to:

* Understand rent distribution
* Analyze trends across years
* Compare rent across counties and provinces
* Study impact of location-based features
* Identify redundant and derived columns

Visualizations include:

* Bar plots
* Group-based aggregations
* Time-based trends

---

## ⚙️ Models Used

Two regression models were implemented and compared:

### 1. Linear Regression

Used as a baseline model to understand linear relationships in the data.

### 2. Random Forest Regressor

Used as an advanced model to capture non-linear patterns and complex feature interactions.

---

## 🔁 Model Evaluation

Models were evaluated using:

* Mean Squared Error (MSE)
* R² Score
* Cross-validation (`cross_val_score`)
* Mean CV score
* Standard deviation of CV score

This ensures both performance and stability are measured.

---

## 📈 Model Comparison

Models were compared using:

* Cross-validation mean score
* Cross-validation standard deviation
* Test R² score
* Test MSE

The final model was selected based on overall performance and generalization ability.

---

## 💾 Model Saving

The trained model is saved using `joblib` for reuse and deployment readiness.

---

## 🎯 Project Objectives

* Predict Irish house rent prices
* Apply complete ML workflow
* Perform EDA-driven feature selection
* Compare ML models scientifically
* Build interview-ready ML project

---

## 📌 Conclusion

This project demonstrates a complete machine learning pipeline including:

* Data understanding
* Feature engineering
* Model training
* Model evaluation
* Model comparison
* Model persistence

It is designed as a structured academic ML project suitable for GitHub portfolios and technical interviews.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib

---

## 👨‍🎓 Author

**B.Tech Student (2nd Year)**
Machine Learning & Data Science Enthusiast

---

## 📎 Note

This project focuses on correct ML fundamentals and honest model evaluation rather than complex architectures, making it suitable for academic learning and interview discussions.
