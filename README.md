# 🏠 House Price Prediction – Prodigy ML Task 01

## 📌 Project Overview
This project implements a **Linear Regression model** to predict house prices based on key features like square footage, number of bedrooms, and number of bathrooms. It is part of a machine learning task to understand regression modeling and feature engineering in real-world datasets.

---

## 🎯 Objective
Build a predictive model that estimates house prices using:
- Living area (square footage)
- Number of bedrooms
- Number of bathrooms

---

## 📊 Dataset
The dataset includes:
- `GrLivArea` – Above ground living area (sq. ft.)
- `BedroomAbvGr` – Number of bedrooms
- `FullBath` – Number of full bathrooms
- `HalfBath` – Number of half bathrooms
- `SalePrice` – Target variable (house price)

**Feature Engineering:**  
- `TotalBathrooms = FullBath + 0.5 × HalfBath`

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Loaded dataset using pandas  
- Checked for missing values  
- Created `TotalBathrooms` feature  

### 2. Model Building
- Linear Regression model using `scikit-learn`  
- Trained on selected features  

### 3. Prediction
- Applied the trained model to test data  
- Generated predictions and saved as CSV (`house_price_predictions.csv`)

---

## 📈 Output
- CSV file with:
  - `Id`
  - `SalePrice` (predicted values)

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- Scikit-learn  
- Google Colab  

---

## 🧠 Key Learnings
- Regression model implementation  
- Feature engineering and selection  
- Data preprocessing  
- Handling real-world datasets  
- Generating predictions and saving results

---

## 🚀 Future Improvements
- Add more relevant features for better accuracy  
- Try advanced models like Random Forest or XGBoost  
- Perform hyperparameter tuning and cross-validation  

---

## 📌 How to Run
1. Open the notebook in Google Colab  
2. Upload the `train.csv` and `test.csv` files  
3. Run all cells  
4. Download `house_price_predictions.csv` from Colab

---

## 📂 File Structure
