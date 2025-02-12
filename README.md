# 🚗 Car Price Prediction using Linear Regression

## 📌 Overview
This project uses **linear regression** to predict car prices based on various features such as **KM_ Driven, age, brand, fuel type, and other specifications**. The goal is to create an efficient model that helps users estimate a car’s market value using historical data.

---

## 📊 Dataset
The dataset consists of multiple features that impact car prices. Some of the key attributes include:
- **Brand**: The manufacturer of the car (e.g., Toyota, Ford, BMW).
- **Model**: The specific model of the car.
- **Year**: Manufacturing year of the vehicle.
- **Mileage**: Distance the car has been driven.
- **Fuel Type**: Petrol, Diesel, Electric, etc.
- **Transmission**: Manual or Automatic.
- **Engine Power**: Power output of the car’s engine.
- **Price** (Target variable): The actual selling price of the car.

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

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone <repo-link>
cd car-price-prediction
