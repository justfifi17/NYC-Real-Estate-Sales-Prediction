# 🏙 NYC Real Estate Sales Prediction

This project uses **machine learning models** to predict real estate sales prices in New York City from 2016-2017. The dataset includes property details like borough, neighborhood, building class, and sales prices.

## Models used 

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
 
## 📊 Features

- **Data Preprocessing**: Handled missing values, removed unnecessary columns, and transformed skewed data using log transformation.
- **Modeling**: Developed models using **Linear Regression**, **Random Forest**, **Gradient Boosting**, **XGBoost**, and others.
- **Best Model**: Random Forest with **RMSE** of 0.45 and **R²** of 0.76 was chosen for its strong performance and feature importance insights.

## 🛠️ Technologies Used

- **Python**: Core language.
- **Pandas, NumPy**: Data manipulation.
- **Seaborn, Matplotlib**: Visualization.
- **Scikit-learn, XGBoost**: Machine learning algorithms.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the model:
   ```bash
   python real_estate_sales_prediction.py

## 📈 Results
- Random Forest achieved the best results with an R² of 0.76.
- Featured models were evaluated based on RMSE and R².
## 🧪 Tests
- Train-Test Split: Split data into training (80%) and testing (20%) sets.
- Cross-validation: Performed 5-fold cross-validation to evaluate model performance.
- Hyperparameter Tuning: Used GridSearchCV to tune the hyperparameters for Random Forest and XGBoost models.
- Model Evaluation: Assessed models based on RMSE, MAE, and R².

