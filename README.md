# 🏠 House Price Prediction using Machine Learning

Welcome to my beginner-level machine learning project where I predicted house prices using regression models on a real-world dataset! This was my first hands-on attempt to implement a complete ML pipeline, from data preprocessing to model evaluation. The project is inspired by the [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

---

## 📌 Project Overview

- **Goal**: Predict the sale price of houses based on various features (like number of rooms, location, year built, etc.)
- **Model Used**: Linear Regression (with room to expand to other models later)
- **Metric**: Mean Absolute Error (MAE)

---

## 🔧 Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib / Seaborn (optional for EDA)
- Jupyter Notebook

---

## 🧠 Workflow

1. **Data Loading & Inspection**
   - Loaded train/test datasets
   - Identified missing values and object types

2. **Data Preprocessing**
   - Handled missing values
   - One-hot encoded categorical features
   - Converted object types to numerical values

3. **Modeling**
   - Used `LinearRegression` from scikit-learn
   - Fit the model on training data
   - Made predictions on test data

4. **Evaluation**
   - Evaluated the model using **Mean Absolute Error (MAE)**
   - Final MAE: `~22,068`

---

## 📊 Results

- **First attempt**: MAE = `22,068`
- Still room to improve with:
  - Feature engineering
  - Hyperparameter tuning
  - Trying other models (Random Forest, XGBoost, etc.)

---

## 💡 What I Learned

- How to clean and preprocess real-world data
- Encoding categorical variables
- Building a simple regression model in scikit-learn
- Evaluating models with MAE
- How each decision in preprocessing affects final performance

---

## 🚀 What's Next?

- Improve model with better preprocessing
- Try ensemble models like Random Forest or Gradient Boosting
- Submit to Kaggle and track improvement
- Experiment with feature importance and selection

---

## 📝 Author

👨‍💻 Varad – Computer Science Student  
📫 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/)  


---

## 🌟 Final Thoughts

This was my first step into the world of ML projects – not perfect, but a real learning experience. If you're also starting out, feel free to fork this repo and experiment further!

---
