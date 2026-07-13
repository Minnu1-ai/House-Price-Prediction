# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview

This project builds an end-to-end Machine Learning pipeline to predict house sale prices using the Ames Housing dataset. The workflow covers data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, hyperparameter tuning, and model persistence.

The objective is to compare multiple regression algorithms and identify the best-performing model for accurate house price prediction.


## 📂 Dataset

- **Dataset:** Ames Housing Dataset
- **Target Variable:** `SalePrice`
- **Problem Type:** Supervised Machine Learning (Regression)


## 🚀 Project Workflow

- Data Loading
- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Log Transformation of Target Variable
- Categorical Feature Encoding
- Model Training
- Model Evaluation
- Model Comparison
- Cross Validation
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Saving with Joblib


## 🛠️ Feature Engineering

Several new features were created to improve model performance:

- HouseAge
- RemodelAge
- TotalBathrooms
- TotalPorchSF
- TotalSF
- TotalLivingArea

These engineered features capture additional information about the properties beyond the original dataset.


## 🤖 Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor


## 📊 Model Evaluation

The models were evaluated using:

- R² Score
- Root Mean Squared Error (RMSE)
- 5-Fold Cross Validation

Hyperparameter tuning was performed using **GridSearchCV** to improve the performance of the best model.


## 📈 Visualizations

The notebook includes several visualizations, including:

- Missing Value Analysis
- Target Variable Distribution
- Correlation Analysis
- Feature Relationships
- Actual vs Predicted Values
- Residual Plot
- Feature Importance


## 💾 Model Persistence

The final trained model is saved using **Joblib**, making it ready for future predictions or deployment.


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib


## 📌 Key Highlights

✔ Complete end-to-end Machine Learning pipeline

✔ Data preprocessing and feature engineering

✔ Multiple regression model comparison

✔ Cross-validation for robust evaluation

✔ Hyperparameter tuning using GridSearchCV

✔ Feature importance analysis

✔ Model serialization using Joblib


## 🎯 Results

Among all evaluated models, the tuned **Random Forest Regressor** achieved the best overall performance, demonstrating strong predictive capability and good generalization on unseen data.


## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook house-price-prediction.ipynb
```

4. Run all cells.

---

## 👨‍💻 Author

**Minahil Fatima**

Computer Science Student | Machine Learning Enthusiast


⭐ If you found this project useful, consider giving it a star.
