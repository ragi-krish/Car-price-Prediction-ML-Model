# Car-price-Prediction-ML-Model


**Problem Description**

A Chinese automobile company aspires to enter the US market by setting up its manufacturing unit and producing cars locally to compete with US and European counterparts. The company contracted an automobile consulting firm to understand the factors affecting car prices in the American market, as these may differ significantly from the Chinese market.

The key objectives include:

1. Identifying significant variables in predicting car prices.
1. Understanding how well these variables describe car prices.

The consulting firm has collected a large dataset from various market surveys, representing different types of cars in the American market.

**Business Goal**

The goal is to model car prices based on the given independent variables. The insights will help management:

- Understand pricing dynamics in the new market.
- Design cars and strategies to meet specific price levels.
- Create a roadmap for market entry and competition.

**Dataset**

The dataset contains information about cars in the American market. [Dataset link](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link).

-----
**Key Components**

**1. Loading and Preprocessing** 

- Load the dataset using pandas.
- Handle missing values using techniques such as mean/mode imputation or dropping missing data.
- Perform encoding for categorical variables using techniques like one-hot encoding and label encoding.
- Normalize or scale numerical features using StandardScaler or MinMaxScaler.
- Split the dataset into training and testing sets.

**2. Model Implementation** 

Implemented the following regression algorithms:

1. **Linear Regression**
   1. A baseline model to understand the linear relationship between predictors and car prices.
1. **Decision Tree Regressor**
   1. A non-linear model capturing complex relationships.
1. **Random Forest Regressor**
   1. An ensemble method reducing overfitting and improving accuracy.
1. **Gradient Boosting Regressor**
   1. A boosting algorithm that builds models sequentially to reduce errors.
1. **Support Vector Regressor**
   1. A kernel-based method for regression with robustness to outliers.

**3. Model Evaluation** 

Evaluation metrics used to compare model performance:

- **R² (Coefficient of Determination):** Measures how well the model explains variability in the target variable.
- **Mean Squared Error (MSE):** Penalizes larger errors.
- **Mean Absolute Error (MAE):** Measures average magnitude of errors.

Comparison table showcasing the performance of all models.

**4. Hyperparameter Tuning** 

- Performed hyperparameter tuning using GridSearchCV for the best-performing model.
- Tuned parameters include:
  - Number of estimators
  - Learning rate
  - Max depth
  - Subsample ratio
- Observed improvement in model accuracy post-tuning.
-----
**Conclusion**

1. **Best-Performing Model**:
   1. The **Gradient Boosting Regressor** emerged as the best-performing model with the highest R² score 0.889178 and lowest error metrics MAE- 0.139806 and RMSE- 0.173404).
1. **Model Utility**:
   1. The model provides actionable insights into pricing dynamics and helps management design strategies for competitive pricing.


