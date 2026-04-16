# 🍔 Food Delivery Time Prediction

## 📌 Project Overview

This project aims to predict food delivery time using machine learning techniques based on factors such as distance, traffic conditions, weather, and order details. It also classifies deliveries into **Fast** or **Delayed** categories to assist in operational decision-making.

---

## 🎯 Objective

* Predict delivery time using **Linear Regression**
* Classify deliveries as **Fast or Delayed** using **Logistic Regression**
* Analyze key factors affecting delivery performance
* Provide actionable insights to optimize delivery operations

---

## 📊 Dataset Description

The dataset contains information related to food delivery operations, including:

* Distance between restaurant and customer
* Weather conditions
* Traffic conditions
* Vehicle type
* Order cost
* Delivery time (target variable)

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 🔹 Phase 1: Data Collection & Preprocessing

* Loaded dataset using Pandas
* Handled missing values using mean and mode
* Encoded categorical variables using Label Encoding
* Standardized numerical features using StandardScaler

---

### 🔹 Phase 2: Exploratory Data Analysis (EDA)

* Generated descriptive statistics
* Visualized correlations using heatmaps
* Detected outliers using boxplots

---

### 🔹 Phase 3: Feature Engineering

* Created new features like **Rush Hour**
* Calculated distance using Haversine formula (if required)

---

### 🔹 Phase 4: Model Building

#### 📈 Linear Regression

* Used for predicting delivery time
* Evaluation Metrics:

  * Mean Squared Error (MSE)
  * Mean Absolute Error (MAE)
  * R² Score

#### 📊 Logistic Regression

* Used for classification (Fast vs Delayed)
* Evaluation Metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix
  * ROC Curve

---

## 📉 Results & Insights

* Distance is the most significant factor affecting delivery time
* Traffic conditions greatly impact delays
* Deliveries during rush hours are more likely to be delayed
* Weather conditions also influence delivery efficiency

---

## 🚀 Recommendations

* Optimize delivery routes using shortest path algorithms
* Increase delivery staff during peak hours
* Use real-time traffic data for better scheduling
* Train delivery personnel for efficiency improvements

---

## 📁 Project Structure

```
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Time_Prediction.csv
├── Food_Delivery_Time_Prediction.ipynb
├── Final_Report.pdf
├── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
4. Run all cells in the notebook

---

## 📌 Conclusion

This project demonstrates how machine learning can improve delivery time prediction and help businesses optimize operations and enhance customer satisfaction.

