# Rossmann-Sales-Prediction

![image](https://user-images.githubusercontent.com/82259772/130562475-ea493f22-cb6f-4e58-93ff-09e98c986009.png)

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. My work includes various plots and graphs , visualizations , feature engineering , ensemble techniques , different ML algorithms with their respective parameter tuning , analysis and trends . Predictions are of 6 weeks of daily sales for 1,115 stores located across Germany.

In this project, the Kaggle Rossman challenge is being taken on. The goal is to predict the Sales of a given store on a given day. Model performance is evaluated on the root mean square percentage error (RMSPE).
Please install the requirements.txt to reproduce the results:
> pip install -r requirements.txt

It is recommended to use a new environment before running the pip install.

The dataset consists of two csv files: store.csv and train.csv

Data Files:

train.csv holds info about each store.
store.csv holds the sales info per day for each store.

The repo contains main.py that runs the main script from step one until the end.


# 1. Business Problem.

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

# 2. Solution Strategy

My strategy to solve this challenge was:

Step 01: Data Description: Use statistics metrics to identify data distribuctions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

Step 08: Deploy Modelo to Production: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 3. Top 3 Data Insights

Stores with more assortments sell less.

Stores with closer competitors sell more than stores with more distant competitors.

Stores sell less on weekends.

# 4. Machine Learning Model Applied

At this stage, 5 models were used for analysis: *Average - Baseline *Linear Regression *Lasso Regression *Random Forest Regressor *XGBoost Regressor

# 5. Machine Learning Modelo Performance

![Capture](https://user-images.githubusercontent.com/82259772/130566762-9030bd79-0857-4ccd-a3e2-e4a24a0f87a9.PNG)

# 6. Business Results

Below is the six-week forecast.

> Scenario	Values
> * predictions	R$277,437,632.00
> * worst_scenario	R$276,572,719.87
> * best_scenario	R$278,302,519.21

# 7. Conclusions

The sales forecast and the generated insights provide the CEO with valuable tools to decide the amount of budget that is going to be dedicated to the restoration of each store.
