# machine-learning-challenge

![image](https://user-images.githubusercontent.com/17952875/119768642-cd4cb080-be6d-11eb-9b49-200dd1d919f3.png)

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

**Objective**
The goal of this challenge is to construct 2 machine learning models capable of classifying potential exoplanets from the raw data

**Preprocessing**
Using the Python tool MinMaxScaler from Scikitlearn, I scaled the data and split it into training and test datasets. 

**Model selection**
I trained two models: A logistic regression model and a Random Forest Classifier

**Feature selection**
After training both models I removed features which the model determined to be low value and re-ran fitting models.

**Tuning**
Using Grid Search I determined the best training/testing model scores for both models and tuned them and re-ran fitting models.

**Predictions and Results**
After fitting the tuned models, the results are presented below:

![image](https://user-images.githubusercontent.com/17952875/119769377-37198a00-be6f-11eb-9635-7fdf5256848c.png)

As can be seen from this table, the tuned Random Forest model provides an accuracy of 86.04%, slightly higher than the Logistic Regression model @ 85.12%.
