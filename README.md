# **Car Price Prediction using Machine Learning**

# 

### Project Overview



This project predicts the selling price of used cars using Machine Learning techniques. The model is trained on a dataset containing information such as the car's present price, manufacturing year, kilometers driven, fuel type, transmission type, selling type, and number of previous owners.



The objective is to build a regression model that can accurately estimate the selling price of a used car based on these features.





### Dataset



The dataset contains the following features:

* Car\_Name
* Year
* Present\_Price
* Driven\_kms
* Fuel\_Type
* Selling\_type
* Transmission
* Owner
* Selling\_Price (Target Variable)





### Technologies Used



* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn





### Project Workflow



1\. Import Libraries

2\. Load Dataset

3\. Exploratory Data Analysis (EDA)

4\. Data Cleaning

5\. Feature Engineering (Car\_Age)

6\. Data Visualization

7\. Encoding Categorical Variables

8\. Train-Test Split

9\. Model Training

10\. Model Evaluation

11\. Feature Importance Analysis

12\. Prediction and Conclusion





### Machine Learning Models



* Linear Regression
* Random Forest Regressor





### Model Performance



|**Model**|**R² Score**|**MAE**|
|-|-|-|
|Linear Regression|0.8489|1.216|
|Random Forest Regressor|0.9595|0.637|





### Key Findings



* Present Price is the most influential feature in predicting the selling price.
* Car Age and Driven Kilometers also affect resale value.
* Random Forest Regressor achieved the highest prediction accuracy among the tested models.





### How to Run the Project



1\. Clone this repository.

2\. Install the required libraries:

&#x20;  pip install -r requirements.txt

3\. Open 'CodeAlpha\_CarPricePrediction.ipynb' in Jupyter Notebook.

4\. Run all cells sequentially.





### Visualizations



The project includes:



* Distribution of Selling Price
* Car Age vs Selling Price
* Fuel Type Distribution
* Transmission Type Distribution
* Correlation Heatmap
* Actual vs Predicted Prices
* Feature Importance Graph





### Conclusion



This project demonstrates the complete machine learning workflow, from data preprocessing and visualization to model building and evaluation. Among the models tested, the Random Forest Regressor produced the best results with an "R² Score of 0.9595" and a "Mean Absolute Error (MAE) of 0.637", making it the most suitable model for predicting used car selling prices.

