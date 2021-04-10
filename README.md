# Linear-Regresssion-California-House-Price-prediction.
Predict California house prices based on the features using Linear Regression algorithm.

### Objective
The objective is to predict California house prices based on the features using Linear Regression algorithm.

Contents
This project is meant to explore, analyse, visualize and predict if a person have a chances to be diabetic by exploring the following columns:
    1. longitude             
    2. latitude              
    3. housing_median_age    
    4. total_rooms           
    5. total_bedrooms        
    6. population            
    7. households            
    8. median_income         
    9. median_house_value    

### Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataset
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values but there are no null and unwanted values present in the dataset.
    4. Performed Simple Linear Regresssion on one feature('median_income') and a target variable ('median_house_value').
    5. Prediction of Train data
         - We got the score of  - 0.47699 for Train data and RMSE of 83614.87409
    6. Perform Feature Selection using following:
        i.  SelectKBest
        ii. Recurrsive Feature Elimination
    7. Peform Multiple Linear Regression.
    8. Performance of Train data 
         Test RMSE :  71133.17349
         Test SSE :  20887384316170.594
         Test SST :  -177212710209751.7
         Test R2 :  1.117866
   9. Performance of Test data 
         Test RMSE :  71133.17349
         Test SSE :  20887384316170.594
         Test SST :  54105533852322.5
         Test R2 :  0.61395
