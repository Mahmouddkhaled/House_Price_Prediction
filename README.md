\# 🏡 House Price Prediction using Machine Learning



\## 📌 Project Overview

This project aims to predict house prices based on various property features (location, size, condition, etc.).  

We use \*\*machine learning models\*\* to find the best approach for accurate price prediction.



---



\## 📊 Dataset

\- Source: Kaggle House Prices Dataset  

\- Train set: 1460 rows × 81 columns  

\- Target variable: `SalePrice`



---



\## 🛠️ Project Workflow

1\. \*\*Exploratory Data Analysis (EDA)\*\*  

&nbsp;  - Checked missing values  

&nbsp;  - Visualized distributions and correlations  



2\. \*\*Data Preprocessing\*\*  

&nbsp;  - Removed columns with too many missing values  

&nbsp;  - Imputed missing data (median/mode)  

&nbsp;  - One-Hot Encoding for categorical features  



3\. \*\*Model Training\*\*  

&nbsp;  - Linear Regression (baseline)  

&nbsp;  - Random Forest Regressor  

&nbsp;  - XGBoost Regressor  



4\. \*\*Evaluation\*\*  

&nbsp;  - Metrics: RMSE (Root Mean Squared Error), R² Score  

&nbsp;  - Visualization of results  



---



\## 📈 Results



| Model              |   RMSE   | R² Score |

|--------------------|----------|----------|

| Linear Regression  | 51,992   | 0.65     |

| Random Forest      | 28,648   | 0.89     |

| \*\*XGBoost\*\*        | \*\*26,279\*\* | \*\*0.91\*\* |



\- \*\*XGBoost achieved the best performance\*\*, showing strong predictive power.



---



\## 🔑 Key Insights

\- House \*\*quality\*\* and \*\*living area\*\* are the most important factors affecting price.  

\- XGBoost outperforms both Linear Regression and Random Forest.  



---



\## 🚀 Future Improvements

\- Hyperparameter tuning for better model performance.  

\- Advanced Feature Engineering (e.g., new derived features).  

\- Model stacking/ensembling for potential accuracy boost.  



---




