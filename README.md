# **Car Price Prediction using Machine Learning**





### Project Overview



The price of a used car depends on several factors such as the car's age, present market price, fuel type, transmission, ownership history, and distance driven. This project applies Machine Learning techniques to accurately predict the selling price of a used car using historical data.



The project covers the complete Data Science workflow, including data preprocessing, feature engineering, exploratory data analysis (EDA), visualization, model building, model evaluation, and feature importance analysis.







### Objectives



* Analyze factors affecting used car prices.
* Perform data cleaning and preprocessing.
* Apply feature engineering techniques.
* Visualize relationships between different features.
* Build and compare multiple Machine Learning regression models.
* Evaluate model performance using standard metrics.
* Predict the selling price of used cars accurately.







### Dataset Information



The dataset contains information about different used cars along with their selling prices.



#### Features

|**Feature**|**Description**|
|-|-|
|Car\_Name|Name of the car|
|Year |Manufacturing year|
|Present\_Price|Current ex-showroom price (in lakhs)|
|Driven\_kms|Total kilometers driven|
|Fuel\_Type|Petrol, Diesel or CNG|
|Selling\_type|Dealer or Individual|
|Transmission|Manual or Automatic|
|Owner|Number of previous owners|





#### Target Variable

|**Target**|**Description**|
|-|-|
|Selling\_Price|Selling price of the used car (in lakhs)|







### Technologies Used



* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn







### Python Libraries



* python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn









### Data Preprocessing



The following preprocessing steps were performed:



* Dataset inspection
* Missing value analysis
* Feature engineering
* Car age calculation
* Removal of unnecessary columns
* One-Hot Encoding for categorical variables
* Train-Test Split







### Exploratory Data Analysis (EDA)



The following analysis was performed:



* Dataset Overview
* Missing Value Analysis
* Statistical Summary
* Correlation Analysis
* Correlation Heatmap
* Feature Relationship Analysis







### Data Visualizations



The project includes the following visualizations:



* Correlation Heatmap
* Actual vs Predicted Car Prices
* Feature Importance Plot





### Machine Learning Models



Two regression models were implemented and compared.



1. #### Linear Regression
* R² Score: 0.8489
* Mean Absolute Error (MAE): 1.2164







#### 2\. Random Forest Regressor

* R² Score: 0.9595
* Mean Absolute Error (MAE): 0.6369



**Random Forest Regressor achieved the highest prediction accuracy and lowest prediction error.**









### Model Evaluation



The models were evaluated using:



* R² Score
* Mean Absolute Error (MAE)



#### Model Comparison

|**Model**|**R² Score**|**MAE**|
|-|-|-|
|Linear Regression|0.8489|1.2164|
|Random Forest Regressor|0.9595|0.6369|









### Key Insights



* Present Price is the most influential feature in predicting the selling price.
* Car Age negatively affects the resale value.
* Higher kilometers driven generally reduce the selling price.
* Fuel Type and Transmission also contribute to price prediction.
* Random Forest performs significantly better by capturing complex relationships between features.







### Project Output



The project generates:



* Used car price prediction model
* Correlation heatmap
* Feature importance chart
* Actual vs Predicted Car Prices graph
* Performance comparison of regression models







### Conclusion



This project successfully demonstrates the application of Machine Learning in predicting used car prices based on vehicle characteristics.



After comparing multiple regression models, the "Random Forest Regressor" achieved the best performance with:



* R² Score: 0.9595
* Mean Absolute Error (MAE): 0.6369



**The results indicate that Random Forest provides highly accurate predictions and is well-suited for estimating used car prices. Such predictive models can assist buyers, sellers, and dealerships in making informed pricing decisions.**





