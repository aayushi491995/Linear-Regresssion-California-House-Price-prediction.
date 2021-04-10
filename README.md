# Linear-Regresssion-California-House-Price-prediction.
Predict California house prices based on the features using Linear Regression algorithm.

### Objective
The objective is to predict California house prices based on the features using Linear Regression algorithm.

Contents
This project is meant to explore, analyse, visualize and predict if a person have a chances to be diabetic by exploring the following columns:
    1. pregnant - how many times that person has been pregnant
    2. glucose - the level of glucose
    3. bp - Diastolic blood pressure
    4. skin - Triceps skin fold thickness
    5. insulin - 2-Hour serum insulin
    6. bmi - Body mass index (weight in kg/(height in m)^2)
    7. pedigree - DiabetesPedigreeFunction
    8. age - Age (years)
    9. label - target variable whether the person is diabetic or not

### Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataser
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values but there are no null and unwanted values present in the dataset.
    4. Train Test Split
    5. Perform Logistic Regression  on Train data 
         - We can perform logistic Regression on the system as the values to predict are binary in nature i.e., a person can either be                  diabetic or not.
    6. Prediction of Train data
         - We got the accuracy of  - 0.78 for Train data 
    7. Prediction of Test data </ul>
         - We got the Test accuracy of - 0.75, Hence the model is neither underfiting not over fitting.
