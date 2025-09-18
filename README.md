# **🏠 Real Estate Price Prediction & Fraud Detection**

---

# Project Introduction

This project leverages Machine Learning to predict real estate prices and detect fraudulent property listings. By analyzing historical property data and market trends, it aims to provide accurate pricing insights and identify potential scams.  

📅 *Start Date:* 15 Aug 2025  
👨‍💻 *Developer:* Subhranil Dutta  

---

## 📌 Project Goals
1. Predict property prices accurately using historical data and market trends.  
2. Detect fraudulent property listings to prevent scams.  
3. Build an end-to-end ML workflow for real estate analysis.

---

## 💡 Why This Project Matters
Real estate is one of the world’s largest industries, but pricing transparency and fraud detection remain major challenges.  
This project uses AI to predict prices and spot unusual or fake listings, helping buyers, sellers, and property websites make safer and smarter choices.

---

## 📂 Dataset Information
- *Source:*   [Kaggle – India House Price Prediction](https://www.kaggle.com/datasets/ankushpanday1/india-house-price-prediction)  
- *Size:* 39.2 MB
- *Format:* CSV  
- *Features Include:* Location, Area, Bedrooms, Bathrooms, Year Built, Amenities, Furnishing, Price.
- *Target Variable:* Price_in_Lakhs
  
---

## ✨ Features
- Data preprocessing and cleaning (handled 2.5 lakh+ rows × 23 features).  
- Exploratory Data Analysis (EDA) with visualizations: correlation heatmaps, histograms, countplots.  
- Price prediction using regression models (Random Forest, GridSearch tuned).  
- Fraud detection using classification models (XGBoost, GridSearch tuned).  
- Feature selection (Top-K features) and correlation analysis.  
- Hyperparameter tuning with GridSearchCV & RandomizedSearchCV.  
- Model evaluation using *RMSE, Accuracy, Precision, Recall, and F1 Score*.  
- Final comparison: Baseline vs Tuned vs Top-k Features models.  

---

## 📂 Project Structure
- *Phase 0 – Data Foundation & Preprocessing* : Data cleaning, handling missing values, and preparing dataset.  
- *Phase 1 – Model Training & Evaluation (Regression)* : Built baseline regression models for price prediction.  
- *Phase 2 – Price Category Prediction (Classification)* : Built baseline classification models for fraud detection.  
- *Phase 3 – Hyperparameter Optimization* : Tuned regression & classification models using GridSearchCV and RandomizedSearchCV.  
- *Phase 4 – Feature Engineering & Data Enhancement* : Implemented Top-K feature selection, correlation analysis, and data enrichment.  
- *Phase 5 – Project Wrap-Up & Insights Documentation* : Final model comparisons, visualizations (feature importance, predicted vs actual, confusion matrix), and result storage.  

---


## 🛠 Tech Stack
- *Language:* Python  
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy  
- *Environment:* Google Colab  

---

## 📊 Results
- *Best Regression Model* : ✅ Random Forest (Top-K features) → Lowest RMSE.  
- *Best Classification Model* : ✅ XGBoost (GridSearch Tuned) → Highest F1 Score.  
- Models exported as .pkl.  

---
  

---

## 👨‍💻 Author
*Subhranil Dutta*  
CSE | GenAI Learner | AI & ML Enthusiast | Python Developer  
🔗 [GitHub Profile](https://github.com/subhranil-gen-ai)
