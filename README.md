# House Price Prediction

A machine learning project that predicts house prices based on property features such as area, number of bedrooms, bathrooms, stories, parking availability, furnishing status, and other amenities.

## Project Overview

Accurate property valuation is essential for buyers, sellers, and real estate businesses. Traditional methods often rely on manual comparisons and subjective estimates. This project uses Machine Learning techniques to predict house prices and identify the factors that most influence property value.

The project includes:

* Data exploration and preprocessing
* Feature engineering and encoding
* Linear Regression model
* Random Forest Regressor model
* Model evaluation and comparison
* Data visualization and insights


##  Objectives

* Predict house prices using property characteristics.
* Compare the performance of multiple regression models.
* Identify the most influential features affecting house prices.
* Generate actionable insights for real estate decision-making.

##  Dataset

Dataset Source:

Housing Prices Dataset from Kaggle

To download the dataset:
 🔗 https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


## Project Workflow

### 1. Data Exploration

* Load dataset
* Inspect data structure
* Check missing values
* Analyze distributions

### 2. Data Preprocessing

* Remove duplicates
* Handle missing values
* Encode categorical variables
* Prepare feature matrix and target variable

### 3. Model Development

#### Linear Regression

A baseline regression model used for understanding linear relationships between features and house prices.

#### Random Forest Regressor

An ensemble learning model capable of capturing complex and non-linear relationships.

### 4. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 5. Visualization

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot
* Feature Importance Analysis


##  Results

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 970,043 | 1,324,507 | 0.653 |
| Random Forest Regressor | 1,021,546 | 1,400,566 | 0.612 |


### Performance Analysis

The Linear Regression model outperformed the Random Forest Regressor on this dataset, achieving a lower Mean Absolute Error (MAE), lower Root Mean Squared Error (RMSE), and a higher R² Score. This indicates that the relationship between housing features and price is largely linear, allowing the simpler model to generalize better than the ensemble-based Random Forest model.


##  Sample Visualizations

### House Price Distribution
<img width="1255" height="1041" alt="download" src="https://github.com/user-attachments/assets/19af03e5-473a-4640-a565-937d4d0f91e9" />


### Correlation Heatmap
<img width="691" height="545" alt="download" src="https://github.com/user-attachments/assets/910cee76-cbb3-4922-8842-3c010eea2920" />


### Actual vs Predicted Prices
<img width="691" height="545" alt="download" src="https://github.com/user-attachments/assets/90140059-9086-4084-933d-2ce43bf16532" />


##  Key Insights

* Property area is one of the strongest predictors of house price.
* Number of bathrooms and stories significantly affect valuation.
* Premium amenities such as air conditioning and preferred locations increase property value.
* Random Forest generally outperforms Linear Regression due to its ability to model non-linear relationships.

