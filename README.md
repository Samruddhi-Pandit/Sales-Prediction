Description:
This project builds a Machine Learning model to predict product sales based on advertising spending in TV, Radio, and Newspaper media. The goal is to understand how marketing investments influence sales and to generate accurate predictions using Linear Regression.

Objective:
Analyze the relationship between advertising budget and sales.
Develop a predictive model using Linear Regression.
Measure model performance using evaluation metrics.
Visualize prediction results for better understanding.

Libraries:
Python
Pandas – Data manipulation
NumPy – Numerical computations
Matplotlib – Data visualization
Seaborn – Graphical representation
Scikit-learn – Model training and evaluation

Steps Used:
Step 1: Data Exploration
Loaded dataset using Pandas
Checked data types and structure
Verified missing values

Step 2: Feature Selection
Independent Variables: TV, Radio, Newspaper
Target Variable: Sales

Step 3: Data Splitting
Training Data: 80%
Testing Data: 20%

Step 4: Model Training
Applied Linear Regression algorithm
Trained model using training data

Step 5: Model Evaluation
Performance measured using:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score

Step 6: Visualization
Scatter plot for Actual vs Predicted Sales
Line graph comparison of Sales

Step 7: Future Prediction
Predicted sales for new advertising budget inputs

Outcome:
The model shows a strong correlation between advertising expenditure and sales.
Achieved a high R² score indicating good predictive accuracy.
TV and Radio advertising have higher impact on sales compared to Newspaper.
