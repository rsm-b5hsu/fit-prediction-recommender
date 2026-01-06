# Clothing Fit Prediction & Recommendation (Rent the Runway)

## Goal
Predict whether a rented item will fit a user and recommend items with high fit probability to reduce fit-related returns.

## Data
Rent the Runway reviews dataset (192,544 rentals; 105,571 users; 30,815 items).  
Dataset not included in this repo due to size.

## Approach
- Hybrid Logistic Regression model
- Features: numeric (height/weight/bust/age/rating), categorical (user_id, item_id, category, body type, rented for), and TF-IDF review text
- User-based train/val/test split to reduce leakage

## Results
- ROC-AUC: ~0.855
- Precision@1 (recommendation): ~97.9%

## Files
- `Assignment2.ipynb` — full pipeline (EDA → feature engineering → modeling → evaluation)
- `Assignment2.html` — rendered report
- `Assignment 2.pptx` — presentation slides
