# Predicting House Prices with Linear Regression

## 📌 Project Objective
The objective of this project was to build a predictive model for house prices using **Linear Regression**. The focus was on applying preprocessing steps, feature engineering, and evaluating model performance.

## 🔧 Steps Performed
1. Removed outliers in key features like `price`, `area`, `bedroom`, and `parking`.
2. Applied One-Hot Encoding for categorical variables (`mainroad`, `guestroom`, etc.).
3. Conducted correlation analysis to check feature importance.
4. Standardized numerical features for better model performance.
5. Implemented and compared multiple models:
   - Linear Regression (baseline)
   - Ridge & Lasso Regression (regularization)
   - Random Forest (additional trial)

## 📊 Results
- **Linear Regression:** R² = 0.576, RMSE = 1,029,905  
- **Ridge Regression:** R² = 0.645, RMSE = 942,125  
- **Lasso Regression:** R² = 0.649, RMSE = 936,907  
- **Random Forest:** R² = 0.576  

## 📌 Conclusion
This project demonstrated the complete process of building a predictive model for house prices. 

To check the possibily of multicollinearity i tried ride and lasso also , although it gives slightly better result r2 score 64% and a reduction in error but still not satisfactory , this indicate the dataset itself may not contain enough complexity or variation to achieve significantly higher accuracy.  

Overall, the project highlights the importance of **data cleaning, feature engineering, and model selection** in machine learning workflows. With richer datasets (more features like location details, amenities, etc.), further performance improvements could be achieved.
  

## 🛠 Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## 👤 Author
Ashish Kumar Paswan  
Oasis Infobyte Internship (Data Science Domain)
