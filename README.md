# 🏠 Real Estate Price Prediction & Fraud Detection  

This project predicts real estate prices and detects fraudulent property listings using Machine Learning.  

---

## 📌 Overview
- Predict real estate prices based on property features.  
- Detect fraudulent property listings to prevent scams.  
- Implemented a complete end-to-end ML workflow with preprocessing, feature engineering, model optimization, evaluation, and deployment preparation.  

---

## 📂 Dataset Information  
- *Source:* [Kaggle – India House Price Prediction](https://www.kaggle.com/datasets/ankushpanday1/india-house-price-prediction)  
- *Size:* 39.2 MB  
- *Format:* CSV  
- *Shape:* ~2,50,000 rows × 23 columns  
- *Features Include (partial list):*  
  - Location  
  - Area (sq. ft.)  
  - Bedrooms & Bathrooms  
  - Year Built  
  - Amenities & Furnishing Status  
  - Listing Type & Price  
  - …and several other property-related attributes  

---

## ✨ Features
- Data preprocessing and cleaning (handled 2.5 lakh+ rows × 23 features).  
- Exploratory Data Analysis (EDA) with visualizations: correlation heatmaps, histograms, countplots.  
- Price prediction using regression models (Random Forest, GridSearch tuned).  
- Fraud detection using classification models (XGBoost, GridSearch tuned).  
- Feature selection (Top-K features) and correlation analysis.  
- Hyperparameter tuning with GridSearchCV & RandomizedSearchCV.  
- Model evaluation using *RMSE, Precision, Recall, and F1 Score*.  
- Final comparison: Baseline vs Tuned vs Feature-engineered models.  
- Prepared an interactive Streamlit app (App.py) for predictions & fraud detection.  

---

## 📂 Project Structure
- *Phase 0 – Data Foundation & Preprocessing* : Data cleaning, handling missing values, and preparing dataset.  
- *Phase 1 – Model Training & Evaluation (Regression)* : Built baseline regression models for price prediction.  
- *Phase 2 – Price Category Prediction (Classification)* : Built baseline classification models for fraud detection.  
- *Phase 3 – Hyperparameter Optimization* : Tuned regression & classification models using GridSearchCV and RandomizedSearchCV.  
- *Phase 4 – Feature Engineering & Data Enhancement* : Implemented Top-K feature selection, correlation analysis, and data enrichment.  
- *Phase 5 – Project Wrap-Up & Insights Documentation* : Final model comparisons, visualizations (feature importance, predicted vs actual, confusion matrix), and result storage.  
- *Saved Models/* : Serialized .pkl models for deployment.  
- *App.py* : Streamlit script (prepared for deployment).  

---

## 📊 Results
- *Best Regression Model* : ✅ Random Forest (Top-K features, Tuned) → Lowest RMSE.  
- *Best Classification Model* : ✅ XGBoost (GridSearch Tuned) → Highest F1 Score.  
- Models exported as .pkl for deployment.  

---

## 🚀 Deployment (Future Work)
- Streamlit dashboard (App.py) created for interactive predictions.  
- Next step: Deploy on *Streamlit Cloud* or *Hugging Face Spaces*.  

---

## 👨‍💻 Author
*Subhranil Dutta*  
CSE | GenAI Learner | AI & ML Enthusiast | Python Developer  
🔗 [GitHub Profile](https://github.com/subhranil-gen-ai)
