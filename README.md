# PharmaSolution Sales Forecasting

Accurate sales forecasting is crucial for effective inventory management, resource allocation, and store operations planning. This project focuses on developing a robust and accurate sales forecasting model for PharmaSolution drug stores in Nigeria, empowering store managers with data-driven insights to make informed decisions and optimize their operations.

## Objective

The primary objective of this project is to develop a robust and accurate sales forecasting model for PharmaSolution drug stores in Nigeria. This model will empower store managers with data-driven insights to make informed decisions and optimize their operations.

## Key Steps to Achieve the Objective

- **Exploratory Data Analysis (EDA) and Data Visualization:** Conduct EDA to gain insights into the dataset's characteristics. Visualize data distributions, correlations, trends, and seasonality. Identify patterns that can aid in sales forecasting.

- **Feature Engineering:** Create additional features to improve the model's predictive power.

- **Pipeline for Data Preprocessing and Model Training:** Construct a robust data preprocessing pipeline using ColumnTransformer and Pipeline from scikit-learn. Include components such as imputation for handling missing data, encoding techniques for categorical variables, and scaling for numeric features. Prepare the data for model training by chaining all preprocessing steps and incorporating the chosen estimator.

- **Data Splitting:** Split the dataset into a validation set (40%), a test set (20%), and the remaining portion as the training set, using a random state of 42.

- **Model Training and Validation:** Train the sales forecasting model on the training data using Decision Tree and Random Forest algorithms. Validate the model's performance on the test data.

- **Model Evaluation:** Evaluate the model's performance using RMSE (Root Mean Square Error) and R2-score (Coefficient of Determination).

- **Hyperparameter Tuning:** Utilize GridSearchCV with 3-fold cross-validation to tune the model's hyperparameters.

## Expected Outcomes

By the end of this project, we aim to deliver a reliable and well-performing sales forecasting model for PharmaSolution stores in Nigeria. This model will provide store managers with accurate predictions of daily sales, allowing for improved decision-making and operational efficiency.

## Success Criteria

The project will be considered a success if the developed model achieves a high level of accuracy in sales forecasting, as demonstrated by low RMSE scores and high R2-scores. The insights from EDA and correlation analysis should also provide valuable information for decision-makers.


## Folder Structure

Datasets : contains the datasets used in this project(in csv format).

sales_forcasting.ipynb : Jupyter notebook detailing data preprocessing, analysis & visualizations, feature engineering, and modeling steps.

README.md: Detailed project overview.

Feel free to explore the notebooks to understand the step-by-step process I followed to build and evaluate the predictive model. Your feedback and suggestions are welcome!
