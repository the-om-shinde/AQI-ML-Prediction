# 🌍 India AQI Analysis & Prediction (Machine Learning)

## 📌 Overview

This project focuses on analyzing air quality data across multiple cities in India and predicting **PM2.5 levels** using Machine Learning techniques.

Air pollution is a major environmental issue affecting human health. This project uses data-driven approaches to understand pollution patterns and build predictive models for air quality monitoring.

---

## 🎯 Objectives

* Analyze air quality data across Indian cities
* Perform data preprocessing and transformation
* Identify pollution trends using visualization
* Build machine learning models to predict PM2.5
* Compare model performance and select the best model

---

## 📊 Dataset

The dataset contains air pollution data collected from various cities and monitoring stations.

### Features:

* PM2.5 (Target Variable)
* PM10
* CO
* NO2
* SO2
* OZONE

---

## ⚙️ Workflow

1. Data Collection
2. Data Preprocessing

   * Removed irrelevant columns
   * Handled missing values
   * Applied pivot table transformation
3. Exploratory Data Analysis (EDA)
4. Train-Test Split (80:20)
5. Model Training
6. Evaluation and Comparison

---

## 🤖 Machine Learning Models Used

### 1. Linear Regression

* Assumes linear relationship between pollutants and PM2.5
* Provided **best performance**

### 2. Decision Tree

* Captures non-linear relationships
* Prone to overfitting

### 3. Random Forest

* Ensemble method (multiple decision trees)
* Better than Decision Tree but not best

---

## 📈 Evaluation Metrics

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**

---

## 📊 Results

| Model             | MAE   | RMSE  | Performance |
| ----------------- | ----- | ----- | ----------- |
| Linear Regression | 15.66 | 20.49 | ⭐ Best      |
| Decision Tree     | 17.71 | 25.78 | Overfitting |
| Random Forest     | 16.66 | 22.58 | Moderate    |

### 🔍 Key Insight:

Linear Regression performed best because the dataset shows a **linear relationship between pollutants and PM2.5**.

---

## 📊 Key Observations

* PM2.5 is strongly influenced by PM10, NO2, and CO
* Some cities show significantly higher pollution levels
* Pollution distribution varies across regions
* Most values fall in moderate pollution range with some extreme cases

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

AQI-ML-Prediction/
│
├── AQI_ML_Prediction.ipynb
├── aqi2.csv
├── README.md

---

## 🚀 Conclusion

This project demonstrates how Machine Learning can be used to analyze environmental data and predict air pollution levels effectively.

The results highlight that **simpler models like Linear Regression can outperform complex models** depending on the dataset characteristics.

---

## 🔗 Related Project

📊 Power BI Dashboard:
https://github.com/the-om-shinde/AQI-Analysis-Dashboard

---

## 📚 References

* Scikit-learn Documentation
* Pandas Documentation
* Kaggle Air Quality Dataset
* Machine Learning Books
