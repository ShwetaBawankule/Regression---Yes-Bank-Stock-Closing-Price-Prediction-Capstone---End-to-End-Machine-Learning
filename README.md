# Regression---Yes-Bank-Stock-Closing-Price-Prediction-Capstone---End-to-End-Machine-Learning
This repository contains the code and dataset for predicting the closing price of Yes Bank stock using regression analysis. The project uses a dataset containing historical stock prices of Yes Bank from 2005 to 2020
# Abstract
This study aims to predict the closing price of Yes Bank stock using regression analysis. The study uses a dataset containing historical stock prices of Yes Bank from Jully 2005 to November 2020. The dataset includes variables such as opening price, highest price, lowest price, and closing price and date. The study applies multiple linear regression and other regression techniques to build models that predict the closing price of Yes Bank stock. The models are evaluated using root mean squared error (RMSE) and mean absolute error (MAE) metrics. We have also taken cross validation score into account to finalize the model. The results indicate that both random regressor and XGBoost perform well in predicting the closing price of Yes Bank stock, with random regressor performed well in accuracy parameter. The study concludes that regression analysis can be a useful tool for predicting stock prices and can be valuable for investors in making informed decisions
# Roadmap & navigation 
# Step 1 : Data collection & cleaning
Collect the historical stock prices of Yes Bank from January 2005 to September 2020. Include variables such as opening price, highest price, lowest price, and closing price and date.
# Step 2 : Data Cleaning & Preprocessing
Clean the dataset by removing any missing values, outliers, or errors. Preprocess the dataset by scaling or normalizing the features as necessary.
# Step 3 :Regression model building
Divide the dataset into training and testing sets. Implement Multiple Linear Regression and Support Vector Regression (SVR) models to predict the closing price of Yes Bank stock. Tune the models by adjusting the hyperparameters to optimize performance.
# Step 4:Model Evaluation 
Evaluate the models' performance using root mean squared error (RMSE) and mean absolute error (MAE) metrics. Compare the performance of the models to determine which one performs better.
# Step 5 :Results & conclusion 
Present the results of the regression analysis. Discuss the implications of the results and their potential impact on investors. Provide conclusions and suggestions for future research.

After implementing six regression model and analyzing theri respective performance matrics we came to the conclusion that the "Optimal_RandomRegression" and XGBRegressor are top performing models with respect to all the matrics. But when we look for the cross validation score and other factores such as time complexity, we select the Optimal_RandomForest as a final deployment model.


