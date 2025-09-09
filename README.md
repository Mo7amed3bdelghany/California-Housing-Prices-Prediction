# 🏡 California Housing Prices Prediction  

This project predicts **housing prices in California** using machine learning regression models.  
The dataset is obtained from **Kaggle API**, and different regression algorithms are compared to identify the best-performing model.  

---

## 📂 Dataset  

- **Source:** Kaggle – California Housing Prices Dataset  
- **Download Method:** Kaggle API  

## ⚙️ Project Workflow

1. Data Collection

   - Dataset downloaded directly from Kaggle API.

2. Data Preprocessing

   - Checked and handled missing values.

   - Feature scaling where necessary.

   - Train/Test split for evaluation.

3. Modeling

 - Built and evaluated two models:

    - Linear Regression

    - Random Forest Regressor

4. Evaluation Metric

    - Used R² Score to evaluate model performance.


## 🚀 Tech Stack

- Python 🐍

- Pandas & NumPy (data preprocessing)

- Matplotlib / Seaborn (data visualization)

- Scikit-learn (models + evaluation)

- Kaggle API (dataset download)



📈 Future Work

- Hyperparameter tuning for Random Forest.

- Experiment with advanced models like XGBoost or LightGBM.

- Deploy the model using Streamlit for interactive housing price predictions.

## ✨ Final Note

This project demonstrates the power of **machine learning** in real estate pricing.
While **Linear Regression** provides a simple baseline, the R**andom Forest Regressor** achieved the best performance with an ***R² score of 0.822***, making it a solid model for predicting California housing prices.