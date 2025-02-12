# 🚗 Car Price Prediction using Linear Regression

## 📌 Overview
This project uses **linear regression** to predict car prices based on various features such as **KMs_Driven, age, brand, fuel type, and other specifications**. The goal is to create an efficient model that helps users estimate a car’s market value using historical data.

---

## 📊 Dataset
The dataset consists of multiple features that impact car prices. Some of the key attributes include:
- **Brand**: The manufacturer of the car (e.g., Toyota, Ford, BMW).
- **Year**: Manufacturing year of the vehicle.
- **KMs_Driven**: Distance the car has been driven.
- **Fuel Type**: Petrol, Diesel, Electric, etc.
- **Transmission**: Manual or Automatic.
- **Present Price**: The actual price of the car.
- **Selling Price** (Target variable): The actual selling price of the car.

---

## 🛠️ Technologies Used
This project is built using:
- **Python** (Primary programming language)
- **NumPy & Pandas** (Data manipulation and preprocessing)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-Learn** (Machine learning model implementation)

---

## 🔄 Data Preprocessing
Before training the model, the dataset undergoes thorough preprocessing:
1. **Handling Missing Values**: Imputing missing data using mean, median, or mode.
2. **Encoding Categorical Variables**: Converting non-numeric features (Brand, Fuel Type, Transmission) into numerical format using **One-Hot Encoding**.
3. **Feature Scaling**: Standardizing numerical features to ensure uniformity.
4. **Splitting Data**: Dividing the dataset into training and testing sets (e.g., **80% train, 20% test**).

---

## 🏗️ Model Training
- **Linear Regression** is used to establish relationships between input features and the target price.
- The model is trained using **Scikit-Learn’s LinearRegression** class.
- Performance is evaluated using:
  - **R² Score** (Explained Variance)
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**

---

## 📈 Data Visualization
The project includes exploratory data analysis (EDA) with visualizations:
- **Correlation Heatmap** to analyze feature relationships.
- **Scatter Plots** to visualize price vs. key factors.
- **Histogram & Boxplots** to understand data distribution.

---
