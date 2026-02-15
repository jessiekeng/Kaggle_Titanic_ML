# Titanic - Machine Learning from Disaster 🚢

This repository contains my solution for the legendary Titanic ML competition on Kaggle. The goal is to predict whether passengers survived the shipwreck based on features like age, sex, and ticket class.

## 🚀 Project Overview
In this project, I performed exploratory data analysis and built a **Random Forest Classifier** to predict survival outcomes. I focused on feature engineering to capture historical "Women and Children First" patterns.

## 🛠️ Key Features Used
* **Sex**: The most significant predictor of survival.
* **Pclass**: Socio-economic status (1st, 2nd, or 3rd class).
* **Title**: Extracted from names (e.g., 'Master' for young boys) to identify child survivors.
* **FamilySize**: Combined siblings and parents to see how family units affected survival.
* **Age & Fare**: Used median imputation to handle missing data.

## 📊 Results
* **K-Fold Cross-Validation Accuracy**: ~82%
* **Historical Accuracy**: My model successfully predicted a ~39% survival rate, which aligns with the actual 1912 disaster.

### Model Insights
My model leaned heavily into gender and class, correctly identifying that 1st-class women had the highest survival probability, while adult men in 3rd class had the lowest.



## 💻 How to Run
1. Clone the repository.
2. Ensure you have `pandas`, `numpy`, and `scikit-learn` installed.
3. Run the `titanic_model.ipynb` notebook.
